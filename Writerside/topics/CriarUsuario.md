# Criar usuário

Endpoint
```
PUT api/v1/usuario 
```
Web
```
remote-register-user-list.ts
```
Requisição
```json
{
  "pessoaTipo": "Fisica",
  "dadosGerais": {
    "documento": "09891771652",
    "nomeExibicao": "AAA",
    "email": "asdf@gmail.com",
    "telefone": "31995202054"
  },
  "dadosEmpreendimento": [
    {
      "usuarioTipo": "Proprietario",
      "empreendimentoId": "beb2d91a-82c1-491f-cad2-08db789922d6",
      "estruturaId": "89c346e3-2728-4182-a75a-08db7899c233",
      "imovelId": "a07f94d2-baed-4c19-f53d-08db7899c55b",
      "cargoId": null
    }
  ],
  "dadosResponsavel": null,
  "enviarConvite": false,
  "tipoCliente": 2
}
```
Resposta
```json
{
  "usuarioId": "8d482bf9-655c-45a1-bc17-e8cef2d0c707"
}
```