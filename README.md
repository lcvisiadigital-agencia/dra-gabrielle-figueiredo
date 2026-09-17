# Dra. Gabrielle Figueiredo — Landing Page

Landing page de alta conversão para a Dra. Gabrielle Figueiredo, Cirurgiã-Dentista (CRO-AP 02141) em Macapá/AP, especializada em odontologia estética e harmonização orofacial.

O objetivo da página é converter visitantes do Instagram e de buscas no Google em **avaliações agendadas** via WhatsApp — não apenas gerar tráfego.

## 🔗 Acesso

- **Site:** _(adicionar o link após publicar, ex.: `https://dragabriellefigueiredo.com.br`)_
- **Instagram:** [@dra.gabriellefigueiredo](https://www.instagram.com/dra.gabriellefigueiredo)
- **WhatsApp:** [(96) 98416-6019](https://wa.me/5596984166019)

## ✨ Sobre o projeto

A página apresenta, em um fluxo único de rolagem, a proposta de atendimento integrado da Dra. Gabrielle — que une o cuidado estético com o sorriso (facetas de resina, alinhadores SouSmile) à harmonização orofacial e regeneração da pele (Botox, bioestimuladores de colágeno, microagulhamento com PDRN).

Todo o conteúdo foi escrito em primeira pessoa, como se a própria profissional estivesse conversando com quem visita a página, reforçando proximidade e confiança.

## 🧩 Funcionalidades

- Cabeçalho fixo com navegação por âncoras e menu responsivo para dispositivos móveis
- Seção de apresentação (hero) com foto real, selo de CRO e chamadas diretas para agendamento
- Seção "Sobre" em primeira pessoa
- Especialidades organizadas em 3 frentes: **Sorriso**, **Harmonização Orofacial** e **Pele & Regeneração**, cada uma com um link de WhatsApp com mensagem pré-preenchida específica
- Bloco de filosofia de atendimento em destaque
- Passo a passo de como agendar uma avaliação
- Faixa de credibilidade (registro profissional, credenciamento SouSmile, localização)
- Chamada final para conversão
- Rodapé completo com navegação, contato e redes sociais
- Botão flutuante de WhatsApp e botão de voltar ao topo
- Transições e animações leves ao rolar a página (respeitando `prefers-reduced-motion`)

## 🛠️ Tecnologias utilizadas

- **HTML5** com tags semânticas (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3** puro (variáveis CSS, Flexbox e Grid, responsivo mobile-first)
- **JavaScript** vanilla (sem frameworks e sem dependências externas)
- **Google Fonts:** [Fraunces](https://fonts.google.com/specimen/Fraunces) (títulos) e [Manrope](https://fonts.google.com/specimen/Manrope) (texto)

Não há build, bundler ou dependências de instalação — é um projeto **100% estático**.

## 📁 Estrutura do projeto

```
dra-gabrielle-figueiredo/
└── index.html   # HTML, CSS e JavaScript em um único arquivo,
                  # com a foto e a logo já embutidas em base64
```

## ▶️ Como visualizar localmente

Não é necessário nenhum servidor ou instalação. Basta:

1. Baixar/clonar este repositório
2. Abrir o arquivo `index.html` diretamente no navegador

```bash
git clone https://github.com/lcvisiadigital-agencia/dra-gabrielle-figueiredo.git
cd dra-gabrielle-figueiredo
```

## 🚀 Publicação

O arquivo é estático, então pode ser hospedado em qualquer serviço, por exemplo:

- **GitHub Pages:** em Settings → Pages, selecione a branch `main` e a pasta raiz
- **Hospedagem tradicional (cPanel, etc.):** subir o `index.html` para a pasta pública (`public_html` ou `www`)

## 🎨 Personalização

| O que alterar | Onde encontrar no `index.html` |
|---|---|
| Foto da Dra. Gabrielle | `<img>` dentro de `.portrait-frame`, na seção `hero-visual` |
| Logo | `<img>` dentro de `.brand-mark` (aparece no cabeçalho e no rodapé) |
| Número de WhatsApp | Buscar por `wa.me/5596984166019` e substituir em todos os links |
| Textos de cada seção | Diretamente no HTML, dentro de cada `<section>` |
| Cores da identidade visual | Variáveis no topo do `<style>` (`--marsala`, `--gold`, `--champagne`) |

> Foto e logo estão embutidas como `data:image/jpeg;base64,...` diretamente no HTML — não dependem de arquivos externos. Para trocá-las, converta a nova imagem para base64 e substitua o conteúdo do `src`.

## 🔍 SEO e acessibilidade

- Meta tags de descrição, palavras-chave e Open Graph
- Dados estruturados (Schema.org / `Dentist`) para melhorar a exibição em buscas locais
- Link de pular para o conteúdo (`skip link`)
- Textos alternativos em imagens e ícones decorativos marcados com `aria-hidden`
- Contraste de cores e estados de foco visíveis (`:focus-visible`)
- Layout responsivo para web, tablet e smartphone

## 📄 Licença

Uso exclusivo da Dra. Gabrielle Figueiredo / LC Visia Digital. Todo o conteúdo, identidade visual e imagens pertencem à profissional retratada — não reutilizar sem autorização.

---

Desenvolvido por **LC Visia Digital**.
