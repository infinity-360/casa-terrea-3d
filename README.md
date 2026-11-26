# Casa Térrea 3D

Tour virtual 3D de uma casa térrea com 3 suítes, cozinha gourmet e piscina com hidromassagem, montado a partir da planta baixa.

**Ver online:** https://infinity-360.github.io/casa-terrea-3d/

## O que tem

- Tour guiado pelos 12 ambientes, com legendas e música gerada por código
- Caminhada livre em primeira pessoa (WASD + mouse no computador, joystick no celular)
- Vista de cima sem telhado
- 3 estilos de decoração: moderno, escandinavo e luxo aconchegante
- Horário do dia: manhã, pôr do sol e noite com luzes acesas
- Tela de boas-vindas e botão de contato
- Móveis, plantas e carros em 3D real (modelos glTF), pisos com textura de foto e céu fotográfico

## Como personalizar

Os dados do cliente ficam no bloco `<script id="client">` no início do `index.html`:

```json
{
  "empreendimento": "Casa Térrea com Piscina",
  "endereco": "[Endereço do imóvel]",
  "preco": "[Preço]",
  "contatoNome": "[Seu nome]",
  "contatoTelefone": "[Seu telefone]",
  "whatsapp": ""
}
```

`whatsapp` aceita só números com DDI e DDD (ex.: `5544999999999`). Quando preenchido, aparece o botão "Chamar no WhatsApp".

## Observações

As medidas foram estimadas pela escala dos móveis da planta, que não tem cotas. Imagens ilustrativas.

Feito com [Three.js](https://threejs.org/) r128. Por Infinity 360.

## Créditos dos arquivos em `assets/`

- Ferrari 458 Italia: modelo de [vicent091036](https://sketchfab.com/models/57bf6cc56931426e87494f554df1dab6), CC BY 4.0 (via exemplos do three.js)
- Sofá Glam Velvet: Eric Chadwick / Khronos glTF Sample Assets, CC BY 4.0
- Poltrona Sheen Chair: Eric Chadwick / Khronos glTF Sample Assets, CC0
- Cadeira de jantar, mesa de centro, plantas, texturas de piso e grama, céu (kloofendal_48d_partly_cloudy_puresky): [Poly Haven](https://polyhaven.com), CC0

Texturas de concreto e grama foram ajustadas de cor; texturas reduzidas para 1024 px.
