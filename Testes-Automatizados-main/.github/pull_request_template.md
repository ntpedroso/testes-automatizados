## Tipo de Alteração

- [ ] Nova funcionalidade (`feat`)
- [ ] Correção de bug (`fix`)
- [ ] Refatoração ou melhoria técnica (`refactor`)
- [ ] Atualização de documentação (`docs`)

## Issue Relacionada

Closes #<!-- Número da Issue aqui, ex: Closes #42 -->

## Descrição das Alterações

<!-- Descreva de forma concisa o que foi desenvolvido ou corrigido nesta entrega -->
- Implementado endpoint `GET /voluntarios` com suporte a filtros por habilidade.
- Adicionada validação de paginação (limite máximo de 50 registros por página).

## Checklist da Definição de Pronto (DoD)

- [ ] O código foi compilado/executado sem erros ou warnings no console.
- [ ] Formatadores e linters foram executados com sucesso.
- [ ] Testes unitários/integração foram criados ou atualizados e estão passando.
- [ ] Não há dados sensíveis (senhas, chaves de API, `.env`) incluídos nos commits.
- [ ] A documentação da API / README foi atualizada se aplicável.

## Evidências de Teste

<!-- Anexe capturas de tela (para frontend) ou payloads JSON de resposta (para backend) -->

```json
{
  "total": 1,
  "voluntarios": [
    {
      "id": 1,
      "nome": "Maria Silva",
      "habilidade": "Logística"
    }
  ]
}
```