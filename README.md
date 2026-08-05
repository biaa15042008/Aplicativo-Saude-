<div align="center">

# 💙 Aplicativo Saúde

**App completo de saúde pessoal para monitorar glicemia, pressão arterial, IMC, hidratação, medicamentos, vacinas e muito mais — tudo em um só lugar, com dicas de bem-estar e acesso rápido a emergências.**

![status](https://img.shields.io/badge/status-concluído-brightgreen?style=for-the-badge)
![react-native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![mysql](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</div>

<br>

<p align="center">
  <img height="250" width="145" alt="Emergências" src="https://github.com/user-attachments/assets/1c83a733-99e8-478b-9f09-4e06be25f847" />
  <img height="320" width="170" alt="Pressao" src="https://github.com/user-attachments/assets/62e85b6d-8824-4a81-a825-688b103b60e5" />
  <img height="370" width="195" alt="Tela inicial" src="https://github.com/user-attachments/assets/2f7ae321-52e7-4c01-b7a3-fdf15616f943" />
  <img height="320" width="170" alt="Dicas" src="https://github.com/user-attachments/assets/b4b329ca-e89d-48ae-84c7-f8f190c57cf7" />
  <img height="250" width="140" alt="Vacinas" src="https://github.com/user-attachments/assets/9a2d2acd-4097-49a6-9d48-8a574907b029" />
</p>

<br>

## ✨ Funcionalidades

<div align="center">

| | Funcionalidade | Descrição |
|:---:|---|---|
| 🩸 | **Monitor de Glicemia** | Registro e histórico de níveis de glicose, com gráficos de evolução |
| ❤️ | **Pressão Arterial** | Acompanhamento de sistólica/diastólica com alertas de valores fora do padrão |
| ⚖️ | **Cálculo de IMC** | Cálculo automático do Índice de Massa Corporal com classificação |
| 💧 | **Hidratação** | Lembretes e controle da quantidade de água ingerida ao longo do dia |
| 💊 | **Medicamentos** | Cadastro de remédios, horários e notificações de lembrete |
| 💉 | **Carteira de Vacinas** | Histórico vacinal com data das próximas doses |
| 🌿 | **Dicas de Bem-estar** | Conteúdo sobre alimentação, sono e saúde mental |
| 🚨 | **Emergências** | Acesso rápido a contatos e serviços de emergência |

</div>

<br>

## 🛠️ Tecnologias utilizadas

<div align="center">

| Camada | Tecnologia |
|---|---|
| 📱 **Front-end (Mobile)** | React Native |
| ⚙️ **Back-end** | Laravel (PHP) |
| 🗄️ **Banco de dados** | MySQL |
| 🎨 **Design** | Canva |

</div>

<br>

## 🚀 Como rodar o projeto

### Pré-requisitos
- Node.js instalado
- PHP e Composer instalados
- **XAMPP** instalado e rodando (Apache + MySQL) — use o **phpMyAdmin** para visualizar/gerenciar o banco de dados
- Um emulador Android/iOS ou o app **Expo Go** no celular 

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/biaa15042008/Aplicativo-Saude-.git
cd Aplicativo-Saude-
```

### 2️⃣ Rodar o back-end (Laravel)
```bash
cd Pam-Laravel/saude
composer install
cp .env.example .env
php artisan key:generate

# Configure o banco de dados no arquivo .env
php artisan migrate

# Popular o banco com os dados iniciais (roles, tipos sanguíneos, frutas, etc.)
php artisan db:seed

# Ou, se quiser rodar cada seeder individualmente:
php artisan db:seed --class=DatabaseSeeder
php artisan db:seed --class=InfoSangueSeeder
php artisan db:seed --class=PerfilFrutaSeeder
php artisan db:seed --class=RoleSeeder

php artisan serve
```

### 3️⃣ Rodar o front-end (React Native)
```bash
cd PAM-Front/appSaude
npm install
npx expo start
```

<br>


## 💌 Contato
 
<div align="center">
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/beatriz-mauricio-figueiro)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:beatrizmauriciofigueiro08@gmail.com)

 Um projeto criado para tornar o monitoramento da saúde pessoal mais simples e acessível.
 
</div>
