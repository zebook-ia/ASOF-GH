# Brand Kit ASOF: Template de Email para Gmail

**Associação Nacional dos Oficiais de Chancelaria do Serviço Exterior Brasileiro**

---

## 1. Identidade Visual para Emails

### 1.1. Objetivo
Padronizar o aspecto visual dos emails enviados pela ASOF via Gmail, garantindo reconhecimento imediato da marca, consistência e legibilidade em todos os dispositivos.

### 1.2. Diretrizes Gerais
- **Formato**: HTML responsivo compatível com Gmail (desktop e mobile).  
- **Estilo**: Uso estrito das cores, tipografia e elementos visuais do Brand Kit ASOF.  
- **Conteúdo**: Cabeçalho com logotipo, corpo do email com tipografia legível e botões estilizados, rodapé com informações de contato.  
- **Acessibilidade**: Contraste apropriado (mínimo 4.5:1), fontes de tamanho suficiente para leitura em dispositivos móveis (mínimo 14px).

---

## 2. Paleta de Cores no Email

| Nome           | Hex      | Uso no Email                                    |
|----------------|----------|-------------------------------------------------|
| Preto Profundo | `#000000` | Texto principal e corpo do email                 |
| Azul Escuro    | `#045495` | Fundo de cabeçalho, botões principais, links     |
| Azul Claro     | `#76AEEA` | Hover de botões e links, detalhes de destaque     |
| Azul Pastel    | `#BAD7F7` | Fundo de seções destacadas (avisos, banners)     |
| Lavanda Neutra | `#F3F3FC` | Fundo geral do email (área externa ao container) |

---

## 3. Tipografia Aplicada

| Elemento               | Fonte                      | Tamanho            | Peso       |
|------------------------|----------------------------|--------------------|------------|
| Títulos (H1, H2, H3)   | Roboto Bold                | 24px (H1), 20px (H2), 18px (H3) | 700        |
| Texto de corpo         | Segoe UI / Tahoma / Verdana| 16px               | 400        |
| Botões / CTAs          | Segoe UI Bold / Verdana Bold| 16px              | 600        |
| Texto menor / Notas    | Segoe UI / Tahoma / Verdana| 14px               | 400        |

---

## 4. Elementos Visuais e Componentes

### 4.1. Cabeçalho (Header)
- Fundo: `Azul Escuro (#045495)`.  
- Logotipo centralizado ou alinhado à esquerda, com altura máxima de 60px.  
- Espaçamento interno (padding): 20px acima e abaixo.  

### 4.2. Botões (CTA)
- **Botão Primário**  
  - Fundo: `Azul Escuro (#045495)`  
  - Texto: branco (`#FFFFFF`)  
  - Bordas arredondadas: 4px  
  - Padding: 12px 24px  
  - Link: use atributo `href` inline.  
  - Hover: cor de fundo `Azul Claro (#76AEEA)`, texto permanece branco.

- **Botão Secundário** (opcional)  
  - Fundo: `#FFFFFF`  
  - Borda: 2px sólida `Azul Escuro (#045495)`  
  - Texto: `Azul Escuro (#045495)`  
  - Hover: fundo `Azul Claro (#76AEEA)`, texto branco.

### 4.3. Seções Destacadas
- Fundo: `Azul Pastel (#BAD7F7)`  
- Borda lateral esquerda: 4px sólida `Azul Escuro (#045495)`  
- Texto: `Azul Escuro (#045495)`  
- Padding interno: 16px

### 4.4. Rodapé (Footer)
- Fundo: `Lavanda Neutra (#F3F3FC)`  
- Texto: `#000000`  
- Tamanho de fonte: 14px  
- Itens: informações de contato, links para redes sociais, aviso de confidencialidade.

---

## 5. Template HTML de Exemplo

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Email ASOF</title>
</head>
<body style="margin:0; padding:0; background-color:#F3F3FC;">
  <!-- Container Principal -->
  <table width="100%" cellpadding="0" cellspacing="0" border="0" bgcolor="#F3F3FC">
    <tr>
      <td align="center">
        <table width="600" cellpadding="0" cellspacing="0" border="0" style="background-color:#FFFFFF; margin-top:20px; margin-bottom:20px;">
          
          <!-- Cabeçalho -->
          <tr>
            <td align="center" bgcolor="#045495" style="padding:20px;">
              <img src="https://isbtjhyhcufqzlslghas.supabase.co/storage/v1/object/sign/asof-public/brandkit/LOGO%20ASOF%20st23.png?token=eyJraWQiOiJzdG9yYWdlLXVybC1zaWduaW5nLWtleV9kMGE1MzNlMC1hZGFmLTQxMGEtYjZjOS05YmU2YzY1MDE0MjAiLCJhbGciOiJIUzI1NiJ9.eyJ1cmwiOiJhc29mLXB1YmxpYy9icmFuZGtpdC9MT0dPIEFTT0Ygc3QyMy5wbmciLCJpYXQiOjE3NDkxNDk3MzgsImV4cCI6MTc4MDY4NTczOH0.7mT4kcx48yoWbHouGHZ9V2hg3_vyvVyIYjMu1P5F-xM" alt="Logo ASOF" width="200" style="display:block; max-height:60px;">
            </td>
          </tr>
          
          <!-- Espaçamento -->
          <tr><td style="height:20px;"></td></tr>
          
          <!-- Saudação e Introdução -->
          <tr>
            <td style="padding:0 30px;">
              <h1 style="font-family:'Roboto', sans-serif; font-size:24px; color:#000000; margin:0;">
                Olá, [Nome do Destinatário],
              </h1>
              <p style="font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:16px; color:#000000; line-height:1.5; margin-top:10px;">
                Esperamos que este email encontre você bem. Nesta mensagem, trazemos atualizações importantes sobre as atividades da ASOF.
              </p>
            </td>
          </tr>
          
          <!-- Espaçamento -->
          <tr><td style="height:20px;"></td></tr>
          
          <!-- Seção de Conteúdo Principal -->
          <tr>
            <td style="padding:0 30px;">
              <h2 style="font-family:'Roboto', sans-serif; font-size:20px; color:#045495; margin:0;">
                Destaques do Mês
              </h2>
              <p style="font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:16px; color:#000000; line-height:1.5; margin-top:10px;">
                Acompanhe as novidades:  
                <ul style="font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:16px; color:#000000; line-height:1.5; margin-top:10px; padding-left:20px;">
                  <li>Evento de diplomacia cultural em 15 de julho de 2025.</li>
                  <li>Publicação de relatório anual disponível no portal.</li>
                  <li>Convite para reunião de alinhamento de comissões internas.</li>
                </ul>
              </p>
            </td>
          </tr>
          
          <!-- Seção Destacada -->
          <tr>
            <td style="padding:0 30px;">
              <div style="background-color:#BAD7F7; border-left:4px solid #045495; padding:16px; margin-top:20px;">
                <p style="font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:16px; color:#045495; margin:0;">
                  <strong>Aviso Importante:</strong> Atualize seus dados cadastrais até 30 de junho de 2025.
                </p>
              </div>
            </td>
          </tr>
          
          <!-- Espaçamento -->
          <tr><td style="height:20px;"></td></tr>
          
          <!-- Botão de Ação -->
          <tr>
            <td align="center">
              <a href="https://www.asof.org.br/portal" style="background-color:#045495; color:#FFFFFF; text-decoration:none; font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:16px; font-weight:600; padding:12px 24px; border-radius:4px; display:inline-block;">
                Acessar Portal ASOF
              </a>
            </td>
          </tr>
          
          <!-- Espaçamento -->
          <tr><td style="height:40px;"></td></tr>
          
          <!-- Rodapé -->
          <tr>
            <td align="center" bgcolor="#F3F3FC" style="padding:20px;">
              <p style="font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:14px; color:#000000; margin:0;">
                Associação Nacional dos Oficiais de Chancelaria do Serviço Exterior Brasileiro<br>
                Rua Exemplo, 123 – Brasília, DF – CEP 70000-000<br>
                <a href="mailto:contato@asof.org.br" style="color:#045495; text-decoration:none;">contato@asof.org.br</a> | <a href="https://www.asof.org.br" style="color:#045495; text-decoration:none;">www.asof.org.br</a>
              </p>
              <p style="font-family:'Segoe UI', Tahoma, Verdana, sans-serif; font-size:12px; color:#000000; margin-top:10px;">
                Este e-mail foi enviado para você porque está cadastrado em nossa lista de contatos. Caso não deseje mais receber mensagens, responda “Cancelar Inscrição”.
              </p>
            </td>
          </tr>
          
        </table>
      </td>
    </tr>
  </table>
</body>
</html>
```

**Instruções de Uso**  
1. Copie o código HTML acima.  
2. No Gmail, ao compor um novo email, clique em "Mais opções" (três pontos) e selecione "Texto sem formatação". Cole o HTML no corpo do email.  
3. Ajuste substituindo `[Nome do Destinatário]` e links conforme necessário.  
4. Envie uma prévia para verificar responsividade em desktop e dispositivos móveis.