# 🚀 Guia de Referência: PHP, Laravel & Fullstack

Este guia reflete meu setup otimizado para o desenvolvimento de sistemas complexos (ERPs), focado em performance e produtividade com a stack **Laravel + Vue.js + PostgreSQL**.

---

## 🛠️ Ambiente de Desenvolvimento (VS Code)

Utilizo o recurso de **Perfis do VS Code** para manter um ambiente leve, isolando as ferramentas de PHP/Laravel de outros cenários de trabalho.

### 🧩 Extensões Habilitadas (Perfil Laravel + Fullstack)
*   **Inteligência de Código:**
    *   `PHP Intelephense`: Motor principal de análise estática.
    *   `Laravel Intelephense`: Suporte específico ao framework.
    *   `Laravel Extra Intellisense`: Autocompletar avançado para rotas e views.
*   **Front-end & Interface:**
    *   `Vue (Official)`: Suporte completo para componentes Vue 3.
    *   `Inertia.js`: Navegação rápida entre controllers e views.
    *   `Bootstrap 5 Quick Snippets`: Agilidade na criação de layouts.
*   **Dados & Utilidades:**
    *   `PostgreSQL` & `Database Client JDBC`: Gestão de banco de dados integrada.
    *   `Rainbow CSV`: Organização visual para arquivos de log.
    *   `Dracula Theme Official`: Tema de alto contraste para foco prolongado.

### ⚙️ Configurações de Qualidade
*   **Formatador Padrão:** Intelephense.
*   **Format on Save:** Ativado para garantir padronização automática (PSR).
*   **Sincronização:** Perfil sincronizado via GitHub para portabilidade total.

---

## 🐘 PHP & Composer

| Comando | Descrição |
| :--- | :--- |
| `composer install` | Instala dependências do `composer.json`. |
| `composer update` | Atualiza bibliotecas para a última versão estável. |
| `composer dump-autoload` | Recarrega o mapa de classes (essencial após novas classes). |

---

## 🔥 Laravel Artisan

*   **Servidor:** `php artisan serve`
*   **Eficiência de Banco:**
    *   `php artisan migrate`: Aplica alterações de esquema.
    *   `php artisan migrate:fresh --seed`: Reseta o ambiente com dados fictícios.
*   **Geradores de Código:**
    *   `php artisan make:model Nome -m`: Cria Model e Migration.
    *   `php artisan make:controller NomeController --api`: Cria controlador para APIs.

---

## 📦 NPM (Vite & Assets)

*   `npm run dev`: Hot Reloading para desenvolvimento com Vue/Inertia.
*   `npm run build`: Minificação e otimização para produção.

---

## 🌿 Git (Padronização)

*   `git checkout -b feature/nome`: Organização de funcionalidades em branches.
*   `git pull origin main`: Sincronização constante com o repositório base.
