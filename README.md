# CAIXA v2 — Rede Neural Experimental

Simulador experimental de neurônios biológicos em um único arquivo HTML. Roda no navegador, sem instalação.
Experimental biological neuron simulator in a single HTML file. Runs in the browser, no install.

**Não é uma IA / This is not an AI.** É uma simulação: cada neurônio roda sua própria física o tempo todo.

## O que tem / Features
- Cada neurônio com física própria: potencial, limiar, energia e memória
- Escalas de 1 neurônio a 1 bilhão por grupo (individual ou por grupos)
- Conexões que mudam sozinhas por uso (disparar junto fortalece, não disparar enfraquece)
- Homeostase, ciclo de sono, memória de trabalho da rede e atenção
- Camada de ambiente: serotonina, noradrenalina, acetilcolina e estresse crônico
- Frequência de disparo medida a partir do histórico real
- Exportação em .json, NeuroML2, Brian2 (.py) e NEURON (.mod + .py)
- Autosave no próprio navegador

## Como usar / How to use
Abra o `index.html` no navegador, ou acesse a versão online (GitHub Pages).
O app carrega fontes do Google Fonts e a biblioteca JSZip (cdnjs); sem internet, o visual das fontes muda, mas a simulação segue.

## Recursos opcionais de IA / Optional AI features
O app tem recursos opcionais que usam a API da OpenAI (imagem, texto e voz). Eles só funcionam se você digitar a sua própria chave de API, que é do seu uso e responsabilidade. A chave não vem no arquivo.
Optional features call the OpenAI API and require your own key. No key is included in this repository.

## Limitações / Limitations
Projeto experimental e simplificado. Não substitui modelos validados de neurociência computacional.
Valores biológicos citados no app trazem a fonte na própria tela.
Experimental and simplified; not a validated neuroscience model.

## Autor / Author
segredosocultosdouniverso
Instagram: https://www.instagram.com/segredosocultosdouniverso
YouTube: https://www.youtube.com/@segredosocultosdouniverso
