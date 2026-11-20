# Trabalho 07 – Modelagem e Avaliação de Desempenho com SPN

Avaliação de desempenho do roteador de borda de uma rede universitária
com Redes de Petri Estocásticas (SPN), modelada e simulada na ferramenta Jupiter.

**Autora:** Sthefany Moura Godinho – Sistemas de Informação, UFPI

## Conteúdo do repositório

| Pasta / arquivo | Descrição |
|---|---|
| `modelo/` | Modelo SPN exportado do Jupiter (.json), pronto para importar |
| `resultados/` | Resultados dos experimentos E1 a E4 (.csv) |
| `figuras/` | Figura do modelo e gráficos dos experimentos (.pdf) |
| `artigo_trabalho07_spn.pdf` | Artigo final (formato IEEE) |

## Experimentos

- **E1 – Demanda:** taxa de chegada de 40 a 120 pacotes/ms
- **E2 – Processamento:** 2, 4 e 8 núcleos
- **E3 – Buffer:** 8, 32 e 128 pacotes
- **E4 – Combinado:** 4 e 8 núcleos com enlace de 2,5 Gbps

Configuração da simulação: estacionária, tempo de 100 ms,
confiança de 95% e erro relativo máximo de 5%.

## Como reproduzir

1. No Jupiter, use **File → Import (Local)** e abra o arquivo da pasta `modelo/`.
2. Na tela de análise, use a aba **Scenarios** com os parâmetros de cada experimento.

## Vídeo de apresentação

[[LINK DO VÍDEO](https://youtu.be/3973aiMhEec)]
