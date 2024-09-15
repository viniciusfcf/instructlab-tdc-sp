# instructlab-tdc-sp

## Instalação

- Instalar CLI seguindo os passos: [🧰 Installing ilab](https://github.com/instructlab/instructlab?tab=readme-ov-file#-installing-ilab)

## Passo a passo que executei para gerar este modelo

- `mkdir viniciusfcf-llm && cd viniciusfcf-llm`
- [Install with Apple Metal on M1/M2/M3 Macs](https://github.com/instructlab/instructlab?tab=readme-ov-file#install-with-apple-metal-on-m1m2m3-macs)
- `ilab config init --taxonomy-path taxonomy`
```bash
(venv) ➜  viniciusfcf-llm git:(main) ✗ ilab config init --taxonomy-path taxonomy                                                     
Welcome to InstructLab CLI. This guide will help you to setup your environment.
Please provide the following values to initiate the environment [press Enter for defaults]:
Path to taxonomy repo [taxonomy]: 
`taxonomy` seems to not exist or is empty. Should I clone https://github.com/instructlab/taxonomy.git for you? [Y/n]: 
Cloning https://github.com/instructlab/taxonomy.git...
Path to your model [/Users/vflorent/Library/Caches/instructlab/models/merlinite-7b-lab-Q4_K_M.gguf]: 
Generating `/Users/vflorent/Library/Application Support/instructlab/config.yaml`...
Please choose a train profile to use:
[0] No profile (CPU-only)
[1] A100_H100_x2.yaml
[2] A100_H100_x4.yaml
[3] A100_H100_x8.yaml
[4] L40_x4.yaml
[5] L40_x8.yaml
[6] L4_x8.yaml
Enter the number of your choice [hit enter for the default CPU-only profile] [0]: 
Using default CPU-only train profile.
Initialization completed successfully, you're ready to start using `ilab`. Enjoy!
(venv) ➜  viniciusfcf-llm git:(main) ✗ 
```

- `ilab model download`
- `mkdir taxonomy/knowledge/vinicius && cp ../knowledge/linkedin-profile.md taxonomy/knowledge/vinicius`