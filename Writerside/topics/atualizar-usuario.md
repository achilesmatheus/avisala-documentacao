# Atualizar usuário


Endpoint
```
POST api/v1/usuario
```
Web
```
remote-update-user-list.ts
```
Requisição
```json
{
  "usuarioId": "7a58278c-a94c-4d21-a387-0d2848291e21",
  "cliente": null,
  "imoveis": null,
  "estruturas": null,
  "dadosGerais": {
    "nomeExibicao": "AAA",
    "documento": "99239529080",
    "email": "as@gmail.com",
    "telefone": "31995202054",
    "dataNascimento": "2024-06-04T00:00:00.000Z",
    "generoId": 1,
    "termoAceito": false,
    "photoUrl": "",
    "generoIdError": "",
    "generoIdLabel": "Masculino"
  },
  "dadosResponsavel": null,
  "dadosEmpreendimento": [
    {
      "usuarioEmpreendimentoId": "1e4fdf76-2cdc-43da-56bc-08dc85530423",
      "empreendimentoId": "beb2d91a-82c1-491f-cad2-08db789922d6",
      "usuarioTipo": "Proprietario",
      "estruturaId": "89c346e3-2728-4182-a75a-08db7899c233",
      "imovelId": "d5b315bf-36d2-4ba6-f53a-08db7899c55b",
      "tipoVinculo": "SemVinculo",
      "cargoId": null,
      "cargo": "",
      "inicioMandato": null,
      "fimMandato": null
    }
  ],
  "dadosEmergencia": [],
  "dadosTrabalho": null,
  "dadosResidencia": [],
  "dadosSeguro": [],
  "dadosEnsino": [],
  "dadosPlanoSaude": [],
  "auditoria": {
    "criadoPor": "Achiles Matheus",
    "criadoEm": "2024-06-05T11:31:17.688Z",
    "atualizadoPor": "Achiles Matheus",
    "atualizadoEm": null
  },
  "empreendimentoAtual": null
}
```
Resposta
```json
{
  "usuarioId": "7a58278c-a94c-4d21-a387-0d2848291e21",
  "cliente": null,
  "imoveis": [],
  "estruturas": [],
  "dadosGerais": {
    "nomeExibicao": "AAA",
    "documento": null,
    "email": "as@gmail.com",
    "telefone": "31995202054",
    "dataNascimento": "2024-06-04T00:00:00Z",
    "generoId": 1,
    "termoAceito": false,
    "photoUrl": ""
  },
  "dadosResponsavel": null,
  "dadosEmpreendimento": [
    {
      "usuarioEmpreendimentoId": "1e4fdf76-2cdc-43da-56bc-08dc85530423",
      "empreendimentoId": "beb2d91a-82c1-491f-cad2-08db789922d6",
      "usuarioTipo": "Proprietario",
      "estruturaId": "89c346e3-2728-4182-a75a-08db7899c233",
      "imovelId": "d5b315bf-36d2-4ba6-f53a-08db7899c55b",
      "tipoVinculo": "Conjuge",
      "cargoId": "00000000-0000-0000-0000-000000000000",
      "cargo": null,
      "inicioMandato": null,
      "fimMandato": null
    }
  ],
  "dadosEmergencia": [],
  "dadosTrabalho": null,
  "dadosResidencia": [],
  "dadosSeguro": [],
  "dadosEnsino": [],
  "dadosPlanoSaude": [],
  "auditoria": null
}
```