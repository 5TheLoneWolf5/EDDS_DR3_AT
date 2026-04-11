# | Assessment | Pipelines de CI/CD e DevOps |

### Orquestração de Containers com Kubernetes

Os arquivos YAML estão organizados e presentes na pasta _kubernetes/_ dentro deste repositório.

###### Parte 1:

![](./assets/kubernetes-1.png)

###### Parte 2:

![](./assets/kubernetes-2.png)

### Dockerfile da aplicação esquecida

O arquivo Dockerfile está disponível em <i>devops2026-ufoTracker-main/Dockerfile</i> dentro deste repositório.

- Build da imagem:

![](./assets/build-docker.png)

- Mudança de nome da imagem:

![](./assets/rename-docker.png)

- Push da imagem:

![](./assets/push-docker.png)

- Link para a imagem no repositório Docker:

https://hub.docker.com/r/5thelonewolf5/ufo-tracker

### Workflows Básicos no GitHub Actions

- hello.yml:

https://github.com/5TheLoneWolf5/EDDS_DR3_AT/actions/runs/24226603307

![](./assets/hello-workflow.png)

- tests.yml:

https://github.com/5TheLoneWolf5/EDDS_DR3_AT/actions/runs/24226609118

![](./assets/tests-workflow.png)

- gradle-ci.yml:

https://github.com/5TheLoneWolf5/EDDS_DR3_AT/actions/runs/24226611359

![](./assets/gradle-build-workflow.png)

### Runners, Variáveis e Segurança

- env-demo.yml:

https://github.com/5TheLoneWolf5/EDDS_DR3_AT/actions/runs/24226611376

![](./assets/print-env-workflow.png)

- secret-demo.yml:

https://github.com/5TheLoneWolf5/EDDS_DR3_AT/actions/runs/24226611360

![](./assets/show-hidden-api-secret-workflow.png)

### Diferença entre runners hospedados pelo GitHub e auto-hospedados, citando vantagens e desvantagens:

Os runners hospedados pelo GitHub são máquinas já preparadas pelo GitHub, que executam jobs no workflow.
Já runners auto-hospedados podem ser preparados e customizados pelo desenvolvedor no repositório (com uma máquina dedicada).

Os runners hospedados pelo GitHub oferecem a facilidade e simplicidade de setup, com a desvantagem sendo a falta de flexibilidade e customização. 
Isso é diferente da maneira self-hosted, que te dá a liberdade de configurar um ambiente próprio e personalizado (hardware e software) para a execução dos workflows.
Porém, existe a desvantagem da complexidade e tempo gasto para preparar e manter todo esse ambiente.
