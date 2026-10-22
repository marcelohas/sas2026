# Análise do Programa das Coleções SAS e Integração com a BNCC Computação

Apresentação interativa desenvolvida com **Mira** e **D3.js** para a **Coordenação Pedagógica**, abordando a análise transversal das tecnologias nas Coleções SAS (Ensino Fundamental II - 6º ao 8º ano) e as diretrizes para articulação estruturante com o componente **CHC (Computação, Humanidades e Criatividade)** e a **BNCC Computação**.

---

## 🎯 Objetivo da Apresentação

O material pedagógico do SAS Educação apresenta ampla riqueza investigativa e projetos interdisciplinares. Esta apresentação foi desenvolvida para orientar a coordenação e os professores na transição pedagógica essencial:
- **Do potencial identificado** para o **planejamento intencional da aprendizagem**.
- Articulação entre as abordagens transversais existentes e o componente CHC como espinha dorsal curricular.
- Encaminhamento prático com a recomendação da **Matriz de Articulação Curricular**.

---

## 🖥️ Estrutura dos Slides

A apresentação é composta por 8 slides interativos com coreografia visual em D3.js:

1. **Capa Estratégica:** Programa SAS e a BNCC Computação (6º ao 8º ano).
2. **Diagnóstico (Coleções SAS):** Potencial investigativo, criatividade digital, resolução de problemas e projetos integradores em órbita dinâmica.
3. **Sinergia Disciplinar:** Conexão entre Língua Portuguesa (Seção Click) e Matemática (Mundo Digital), mostrando onde a computação já dialoga com o material.
4. **Ambientes e Plataformas:** Conexão integrada dos ambientes Focos (formação docente), Eureka! (prática gamificada) e Avaliações/Relatórios (dados de acompanhamento).
5. **Ponto Crítico (Três Camadas Pedagógicas):** Diferenciação entre Uso Instrumental, Abordagem Transversal e Desenvolvimento Intencional (BNCC).
6. **Articulação Curricular (O CHC como Espinha Dorsal):** O componente CHC garantindo progressão nos eixos de Pensamento Computacional, Mundo Digital e Cultura Digital sobre as aplicações reais do SAS.
7. **Encaminhamentos (Cinco Etapas):** Trilha sequencial: Mapear SAS → Cruzar BNCC → Diagnosticar → Progressão → Projetos Integradores.
8. **Fechamento e Próximo Passo:** Síntese executiva com recomendação da Matriz de Articulação por ano escolar.

---

## 🚀 Tecnologias Utilizadas

- **HTML5 & CSS3:** Arquitetura limpa com o tema `mira-dark` (estilo glassmorphism, fundo escuro e acentos vibrantes).
- **D3.js (v7):** Animações procedurais em SVG com entrada coreografada e looping contínuo (*Regra Zero do Mira*).
- **100% Offline / Self-contained:** Todas as bibliotecas (D3, fontes Inter) estão vendoradas localmente na pasta `assets/vendor/`, permitindo execução direta sem dependência de internet.
- **Navegação Multimodal:**
  - **Desktop:** Teclas de setas (`←` / `→`), `Espaço`, `PageUp` / `PageDown` e controle flutuante ultra-fino no rodapé.
  - **Mobile:** Toque na tela para avançar, toque na lateral esquerda para voltar e suporte a gestos de deslize (*swipe*).

---

## 📂 Estrutura de Arquivos

```text
Apostilas-SAS/
├── decks/
│   └── 2026-10-22 analise-sas-bncc-computacao/
│       ├── index.html        # Apresentação completa interativa
│       ├── briefing.md       # Briefing pedagógico estruturado
│       ├── assets/           # Fontes e bibliotecas vendoradas
│       ├── mira/             # Módulos de apoio e ferramentas
│       └── references/       # Documentos de apoio e contexto
├── mira.config.json          # Configuração do Mira
└── README.md                 # Documentação do projeto
```

---

## 💡 Como Visualizar

### Opção 1: Direto no Navegador (Offline)
Basta dar dois cliques no arquivo:
`decks/2026-10-22 analise-sas-bncc-computacao/index.html`
Ele abrirá diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Safari) sem necessidade de servidor local.

### Opção 2: Servidor Local (Opcional)
Se preferir rodar em servidor local:
```bash
# Com Node.js / npx
npx serve "decks/2026-10-22 analise-sas-bncc-computacao"

# Ou com Python
python -m http.server 8000 --directory "decks/2026-10-22 analise-sas-bncc-computacao"
```

### Opção 3: Publicar no GitHub Pages
1. No seu repositório no GitHub, vá em **Settings** > **Pages**.
2. Em **Source**, selecione a branch `main` e a pasta `/` (root) ou aponte para a pasta da apresentação.

---

## ⌨️ Comandos de Navegação

| Tecla / Ação | Função |
| :--- | :--- |
| `Seta Direita` / `Seta Abaixo` / `Espaço` / `PageDown` | Avançar para o próximo slide |
| `Seta Esquerda` / `Seta Acima` / `PageUp` | Voltar para o slide anterior |
| `Toque na tela` (Mobile) | Avançar slide |
| `Toque na lateral esquerda` (Mobile) | Voltar slide |
| `Deslize horizontal` (Mobile) | Avançar (esquerda) ou voltar (direita) |
| `P` | Ativar caneta de anotações no slide (Mira Draw) |
| `E` | Modo de edição rápida de textos |

---

Desenvolvido para a equipe pedagógica com o ecossistema Mira.
