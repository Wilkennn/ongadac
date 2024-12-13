
```
ongadac
├─ .env
├─ client
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ public
│  │  └─ vite.svg
│  ├─ src
│  │  ├─ App.jsx
│  │  ├─ assets
│  │  │  ├─ adaclogoredonda.png
│  │  │  ├─ dog.png
│  │  │  ├─ fotocadastro.png
│  │  │  ├─ fotocadastroPet.png
│  │  │  ├─ LandingPage
│  │  │  │  ├─ adotar.png
│  │  │  │  ├─ contato.png
│  │  │  │  ├─ facebook.png
│  │  │  │  ├─ instagram.png
│  │  │  │  ├─ local.png
│  │  │  │  ├─ main-dog.png
│  │  │  │  ├─ voluntario.png
│  │  │  │  └─ wpp.png
│  │  │  ├─ login-image.png
│  │  │  ├─ pqvolunt.png
│  │  │  └─ react.svg
│  │  ├─ components
│  │  │  ├─ BarChartExample.jsx
│  │  │  ├─ ButtonComponent.jsx
│  │  │  ├─ CalendarComponent.jsx
│  │  │  ├─ CalendarPicker.jsx
│  │  │  ├─ CardTarefas.jsx
│  │  │  ├─ ColumnTarefas.jsx
│  │  │  ├─ EventModal.jsx
│  │  │  ├─ FeedbackSection.jsx
│  │  │  ├─ Header.jsx
│  │  │  ├─ LineChartExample.jsx
│  │  │  ├─ ListEventModal.jsx
│  │  │  ├─ Menu.jsx
│  │  │  ├─ Modal.jsx
│  │  │  ├─ Modals
│  │  │  │  ├─ AddPatrocinioModal.jsx
│  │  │  │  ├─ AddTarefaModal.jsx
│  │  │  │  ├─ DeleteTarefaModal.jsx
│  │  │  │  └─ UpdateTarefaModal.jsx
│  │  │  ├─ ModalUpdateTarefa.jsx
│  │  │  ├─ PatrocinioSection.jsx
│  │  │  ├─ PieChartExample.jsx
│  │  │  ├─ PrivateRoute.jsx
│  │  │  ├─ SearchComponent.jsx
│  │  │  └─ VolunteerComponent.jsx
│  │  ├─ main.jsx
│  │  ├─ pages
│  │  │  ├─ AnalisarFeedback.jsx
│  │  │  ├─ Cadastro.jsx
│  │  │  ├─ CadastroPet.jsx
│  │  │  ├─ CadastroVoluntario.jsx
│  │  │  ├─ Calendar.jsx
│  │  │  ├─ Dashboard.jsx
│  │  │  ├─ Formulario.jsx
│  │  │  ├─ HistoricoAdocao.jsx
│  │  │  ├─ LandingPage.jsx
│  │  │  ├─ Layout.jsx
│  │  │  ├─ Login.jsx
│  │  │  ├─ NovoFeedback.jsx
│  │  │  ├─ Patrocinio.jsx
│  │  │  ├─ Perfil.jsx
│  │  │  ├─ PetPefil.jsx
│  │  │  ├─ Pets.jsx
│  │  │  ├─ RecoverPassword.jsx
│  │  │  ├─ RecuperarSenha.jsx
│  │  │  ├─ ResetPassword.jsx
│  │  │  ├─ Tarefas.jsx
│  │  │  └─ Voluntarios.jsx
│  │  ├─ routes
│  │  │  └─ AppRoutes.jsx
│  │  ├─ services
│  │  │  ├─ AuthService.jsx
│  │  │  ├─ EventoService.jsx
│  │  │  ├─ TarefaService.jsx
│  │  │  └─ UserService.jsx
│  │  └─ styles
│  │     ├─ App.css
│  │     ├─ Cadastro.css
│  │     ├─ CadastroPet.css
│  │     ├─ CadastroVoluntario.css
│  │     ├─ CalendarComponent.css
│  │     ├─ Dashboard.css
│  │     ├─ FeedbackList.css
│  │     ├─ FeedbackSection.css
│  │     ├─ Formulario.css
│  │     ├─ Header.css
│  │     ├─ index.css
│  │     ├─ LandingPage.css
│  │     ├─ Layout.css
│  │     ├─ ListEventModal.css
│  │     ├─ Login.css
│  │     ├─ Modal.css
│  │     ├─ Patrocinio.css
│  │     ├─ Perfil.css
│  │     ├─ PerfilPet.css
│  │     ├─ Pets.css
│  │     ├─ RecuperarSenha.css
│  │     ├─ Tarefas.css
│  │     └─ Voluntarios.css
│  └─ vite.config.js
├─ package-lock.json
├─ package.json
└─ server
   ├─ app.js
   ├─ babel.config.cjs
   ├─ jest.config.js
   ├─ package-lock.json
   ├─ package.json
   ├─ prisma
   │  ├─ migrations
   │  │  ├─ 20241204203603_
   │  │  │  └─ migration.sql
   │  │  └─ migration_lock.toml
   │  └─ schema.prisma
   ├─ README.md
   ├─ server.js
   ├─ src
   │  ├─ config
   │  │  └─ upload.js
   │  ├─ controllers
   │  │  ├─ AdocaoController.js
   │  │  ├─ AuthController.js
   │  │  ├─ EventoController.js
   │  │  ├─ FeedbackController.js
   │  │  ├─ PatrocinioController.js
   │  │  ├─ PetController.js
   │  │  ├─ TarefaController.js
   │  │  ├─ TarefaUsuarioController.js
   │  │  └─ UsuarioController.js
   │  ├─ database
   │  │  └─ prismaClient.js
   │  ├─ routes
   │  │  ├─ adocaoRoutes.js
   │  │  ├─ authRoutes.js
   │  │  ├─ eventosRoutes.js
   │  │  ├─ feedbackRoutes.js
   │  │  ├─ patrocinioRoutes.js
   │  │  ├─ petsRoutes.js
   │  │  ├─ routes.js
   │  │  ├─ tarefaRoutes.js
   │  │  └─ usuarioRoutes.js
   │  ├─ services
   │  │  ├─ AdocaoService.js
   │  │  ├─ AuthService.js
   │  │  ├─ EmailService.js
   │  │  ├─ EventoService.js
   │  │  ├─ FeedbackService.js
   │  │  ├─ PatrocinioService.js
   │  │  ├─ PetService.js
   │  │  ├─ TarefaService.js
   │  │  ├─ TarefaUsuarioService.js
   │  │  └─ UsuarioService.js
   │  └─ util
   │     └─ Util.js
   ├─ test
   │  └─ controllers
   │     ├─ AdocaoController.test.js
   │     ├─ AuthController.test.js
   │     ├─ EventoController.test.js
   │     └─ FeedbackController.test.js
   └─ uploads

```