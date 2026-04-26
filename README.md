# App SIBT — Segunda Igreja Batista do Tabuleiro

## Como publicar

1. **Abra o arquivo CHECKLIST.html** no navegador — ele tem todos os passos numerados com links e você vai marcando conforme conclui.

2. **O único arquivo que você precisa editar** é o `index.html`:
   - Abra no VS Code
   - Use Ctrl+F para buscar: `COLE_AQUI`
   - Substitua os 6 valores pelas credenciais do seu projeto Firebase

3. **Arquivos da pasta:**
   - `index.html` — o app completo (único arquivo que precisa editar)
   - `manifest.json` — configuração de PWA (não editar)
   - `sw.js` — funcionamento offline (não editar)
   - `vercel.json` — configuração do Vercel (não editar)
   - `firestore.rules` — regras de segurança do banco (copiar no Firebase)
   - `CHECKLIST.html` — guia visual passo a passo

## Estrutura do banco de dados (Firestore)

Crie estas coleções no Firebase:
- `members` — membros e permissões
- `events` — eventos e cultos
- `inscricoes` — inscrições em eventos
- `finance` — lançamentos financeiros
- `balancetes` — balancetes mensais
- `atas` — atas de reuniões
- `turmas` — turmas de educação
- `materiais` — materiais de cada turma
- `pregacoes` — pregações YouTube/Spotify

## Níveis de acesso

| Permissão | O que pode fazer |
|---|---|
| `admin` | Tudo — somente o Pastor Talles |
| `tesoureiro` | Gerencia finanças e balancetes |
| `secretario` | Gerencia atas, agenda e eventos |
| `professor` | Adiciona turmas e materiais em Educação |
| `member` | Visualiza conteúdo restrito a membros |
| (sem perm) | Acesso público — visitantes |

## Suporte

Se travar em qualquer passo, descreva o problema ao Claude com uma foto da tela de erro.
