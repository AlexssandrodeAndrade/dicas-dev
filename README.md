# 🚀 Guia de Referência: PHP, Laravel & Fullstack

Este guia contém os comandos e configurações essenciais que utilizo no meu dia a dia como desenvolvedor PHP. Ideal para configuração rápida de ambiente e consulta de comandos frequentes.

---

## 🛠️ Configurações VS Code

Para manter o código limpo e organizado, utilizo as seguintes configurações:

*   **Extensão Base:** PHP Intelephense
*   **Format on Save:** Ativado (`Ctrl + ,` -> "Format On Save")
*   **Formatador Padrão:** Intelephense (ou PHP CS Fixer)
*   **Atalhos Úteis:**
    *   `Ctrl + Shift + P`: Paleta de comandos.
    *   `Alt + Shift + F`: Formatar documento manualmente.
    *   `F2`: Renomear símbolos (variáveis/métodos) em todo o projeto.
    *   `Ctrl + P`: Busca rápida de arquivos.

---

## 🐘 PHP & Composer

Gerenciamento de dependências e ambiente PHP.


| Comando | Descrição |
| :--- | :--- |
| `composer install` | Instala dependências do `composer.json`. |
| `composer update` | Atualiza as bibliotecas para a última versão permitida. |
| `composer require <pacote>` | Adiciona uma nova biblioteca ao projeto. |
| `composer dump-autoload` | Recarrega o mapa de classes (útil se uma classe nova não for encontrada). |

---

## 🔥 Laravel Artisan

Os comandos de "mão na massa" do framework.

*   **Servidor:** `php artisan serve` (Inicia o servidor local).
*   **Banco de Dados:**
    *   `php artisan migrate`: Executa as migrações.
    *   `php artisan migrate:rollback`: Volta a última migração.
    *   `php artisan migrate:fresh --seed`: Apaga tudo, recria e popula o banco.
*   **Criação (Make):**
    *   `php artisan make:controller NomeController`: Cria um controlador.
    *   `php artisan make:model Nome -m`: Cria o Model e o arquivo de Migration.
    *   `php artisan make:request NomeRequest`: Cria validação de formulário.
*   **Cache:** `php artisan optimize:clear` (Limpa cache de rotas, views e config).

---

## 📦 NPM (Front-end)

Para projetos com Vite, Mix, Vue ou React.

*   `npm install`: Instala os pacotes do `package.json`.
*   `npm run dev`: Inicia o servidor de assets (Vite) para desenvolvimento.
*   `npm run build`: Compila os arquivos para produção (minificados).

---

## 🌿 Git (Versionamento)

*   `git checkout -b nome-da-branch`: Cria e muda para uma nova branch.
*   `git add .`: Adiciona todas as mudanças para o commit.
*   `git commit -m "mensagem"`: Grava as alterações.
*   `git pull origin main`: Atualiza seu código local com o servidor.
*   `git push origin sua-branch`: Envia suas alterações para o repositório remoto.
*   `git status`: Verifica o que foi alterado.

---

## 💡 Dicas Extras

> **Dica de Ouro:** Sempre verifique o arquivo `.env` antes de rodar as migrações do Laravel para garantir que a conexão com o banco de dados está correta.
