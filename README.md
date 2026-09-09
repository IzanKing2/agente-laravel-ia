# Agente Laravel IA

API en Laravel que expone un agente conversacional con function calling
usando la API de Anthropic (Claude), capaz de ejecutar acciones reales
sobre [dominio: gestor de tareas / CRM].

## Estado
🚧 En desarrollo — Semana 2-3 del roadmap de proyectos.

## Stack
- Laravel 11 · PHP 8.3
- Anthropic API (tool use / function calling)
- SQLite (dev) / MySQL (prod)
- PHPUnit + GitHub Actions

## Instalación
\`\`\`bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
\`\`\`

## Tests
\`\`\`bash
php artisan test
\`\`\`
