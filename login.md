# Login do Administrador

Área restrita para o administrador do restaurante editar os itens do cardápio.

## Campos

| Campo | Tipo | Obrigatório |
|---|---|---|
| E-mail | texto (e-mail) | Sim |
| Senha | texto (senha) | Sim |

## Cores

Usar a paleta de cores pré-selecionada.

## Regras

- O e-mail deve ter um formato válido (`nome@dominio.com`).
- A senha deve ter no mínimo 8 caracteres, 1 caractere especial e 1 número.
- Após 3 tentativas incorretas, exibir mensagem de bloqueio temporário.
- Em caso de sucesso, redirecionar para a área de edição do cardápio.s

## Histórico

- `v1.0` — especificação inicial da tela de login.
- `v1.0.1` — hotfix aplicado na homepage, sem impacto nesta funcionalidade.

---

*Projeto fictício — GCS 2026/1. Sem backend real.*
