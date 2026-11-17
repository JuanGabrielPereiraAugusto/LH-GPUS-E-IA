# 🎮 O Papel das GPUs na Computação Moderna e em Aplicações de IA

Trabalho de pesquisa da disciplina de **Laboratório de Hardware** na **Fatec Taquaritinga** sobre as **placas de vídeo (GPUs)**: como funcionam, quais são os tipos e os componentes, e por que se tornaram a peça central da **Inteligência Artificial**.

📄 **Trabalho completo:** [`O_Papel_das_GPUs_na_Computacao_e_IA.pdf`](O_Papel_das_GPUs_na_Computacao_e_IA.pdf) (10 páginas)

---

## 1️⃣ O que é uma GPU

Um processador especializado em **processamento paralelo massivo**: em vez de poucos núcleos potentes, como a CPU, ela tem **milhares de núcleos menores** fazendo a mesma operação sobre muitos dados ao mesmo tempo.

| GPU **onboard** (integrada) | GPU **dedicada** (offboard) |
|---|---|
| Fica no processador ou na placa-mãe | Placa separada, no slot PCI Express |
| Usa a RAM do sistema | Tem memória própria (VRAM) |
| Para o dia a dia e jogos leves | Para jogos, edição, 3D e IA |

---

## 2️⃣ Tipos de GPU

| Categoria | Para quem | Exemplos |
|---|---|---|
| **Consumer** | Jogos e uso doméstico | GeForce RTX 40/50, Radeon RX 7000/9000, Intel Arc |
| **Profissional** | Workstations (engenharia, 3D, vídeo) | NVIDIA RTX A6000 / RTX 6000 Ada, Radeon Pro W7900 |
| **Servidores e IA** | Data centers e treinamento de modelos | NVIDIA A100, H100, H200, B200 · AMD Instinct MI300X · Intel Gaudi 3 |

### GPUs de IA

| Modelo | Fabricante | VRAM | Uso principal |
|---|---|---|---|
| A100 | NVIDIA | 40 ou 80 GB HBM2e | Treinamento de IA |
| H100 | NVIDIA | 80 GB HBM3 | LLMs e HPC |
| H200 | NVIDIA | 141 GB HBM3e | LLMs de larga escala |
| B200 (Blackwell) | NVIDIA | 192 GB HBM3e | IA generativa |
| Instinct MI300X | AMD | 192 GB HBM3 | Treinamento e inferência |
| Gaudi 3 | Intel | 128 GB HBM2e | Aceleração de IA |

---

## 3️⃣ Componentes de uma GPU

- **Núcleos de processamento:** CUDA Cores (NVIDIA), Stream Processors (AMD), Xe Cores (Intel), além de **Tensor Cores** (IA) e **RT Cores** (ray tracing)
- **VRAM:** GDDR6/GDDR6X nas placas de consumo, **HBM** nas de data center
- **Refrigeração:** a ar, líquida ou passiva
- **Interface:** **PCIe 4.0/5.0 x16**; em servidores, **NVLink** e **Infinity Fabric** ligam várias GPUs

---

## 4️⃣ GPUs e Inteligência Artificial

Redes neurais são, no fundo, **multiplicações de matrizes**, tarefa perfeita para o paralelismo da GPU. Desde a **AlexNet (2012)**, a IA depende delas.

| | CPU | GPU |
|---|---|---|
| Núcleos | Poucos (4 a 64) | Milhares |
| Processamento | Serial, tarefas complexas | Paralelo, tarefas repetitivas |
| Otimizada para | Baixa latência | Alto throughput |
| Em redes neurais | Lento (horas/dias) | Rápido (minutos/horas) |

**Tecnologias e frameworks:** **CUDA** (2006), **Tensor Cores** (desde a arquitetura Volta, 2017), **PyTorch**, **TensorFlow**, **JAX** e **Keras**.

**Aplicações:** treinamento de **LLMs** (GPT, Claude, Gemini, Llama), **geração de imagens** (Stable Diffusion, Midjourney) e **inferência em tempo real** (assistentes, tradução, carros autônomos).

---

## 5️⃣ Fabricantes e tendências

| Fabricante | Posição |
|---|---|
| **NVIDIA** | Líder em IA e data centers, graças ao CUDA |
| **AMD** | Forte no consumer; crescendo em IA com Instinct e ROCm |
| **Intel** | Entrou com Arc (consumer) e Gaudi (IA) |

**Alternativas:** **TPU** (Google) e **NPU** (Apple Silicon, Snapdragon, Intel Core Ultra, Ryzen AI).

**Tendências:** demanda explosiva por GPUs de IA, VRAM cada vez maior (de 40 GB a 192 GB), precisão reduzida (FP8, INT4), GPUs na nuvem, preocupação com o consumo de energia e chips próprios das big techs.

---

## 📚 Referências principais

- NVIDIA. **CUDA Toolkit Documentation**
- KRIZHEVSKY, A.; SUTSKEVER, I.; HINTON, G. **ImageNet Classification with Deep Convolutional Neural Networks**. NeurIPS, 2012.
- GOODFELLOW, I.; BENGIO, Y.; COURVILLE, A. **Deep Learning**. MIT Press, 2016.
- PATTERSON, D.; HENNESSY, J. **Computer Architecture: A Quantitative Approach**. 6. ed. Morgan Kaufmann, 2017.

A lista completa está no PDF.

---

## 🎓 Informações acadêmicas

| | |
|---|---|
| **Instituição** | Fatec Taquaritinga |
| **Curso** | Análise e Desenvolvimento de Sistemas — 3º semestre |
| **Disciplina** | Laboratório de Hardware |
| **Professor** | Gabriel Passatuto Gallo |
| **Trabalho** | Trabalho 1 — Pesquisa |
| **Ano** | 2026 |

## 👤 Autor

**Juan Gabriel Pereira Augusto**
GitHub: [@JuanGabrielPereiraAugusto](https://github.com/JuanGabrielPereiraAugusto)
