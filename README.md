# Laravel/PHP Hello — template Coodesh IDE

Template minimalista para questões tipo IDE (framework `laravel`) no Coodesh.

## O que o candidato encontra

- `index.php` respondendo em `http://<preview-host>/`
- `composer.json` vazio pronto pra `composer require`
- Devfile com dois comandos:
  - `install` → `composer install`
  - `start` → `php -S 0.0.0.0:8000 -t .`

## Estrutura

```
.
├── devfile.yaml   # boot commands + endpoint publico
├── composer.json  # placeholder
├── index.php      # entrada HTTP inicial
└── README.md      # este arquivo
```
