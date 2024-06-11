# Listar usuários

Endpoint
```
GET api/v1/usuario/proprietarios/empreendimento/{empreendimentoId}
```
Web
```
remote-load-user-list.ts
```
Requisição
```json
{
  "empreendimentoId" : "beb2d91a-82c1-491f-cad2-08db789922d6",
  "userType" : ""
}
```
Resposta
```json
{
    "usuarioId": "8405db65-7cd7-4009-beae-4bb56b660578",
    "nome": "YARA DE CASTRO GANME PEDROSO",
    "documento": "13000219854",
    "telefone": "",
    "email": "yaracgpedroso@hotmail.com",
    "convite": null,
    "ativo": true,
    "empreendimentoNome": " CONDOMINIO IMPERIAL PARK",
    "estruturaNome": "IMPERIAL",
    "imovelNome": "000011",
    "imovelId": "1ddcde2f-1b30-4039-f539-08db7899c55b",
    "inadimplente": false,
    "tableData": {
        "id": 0
    }
}
```