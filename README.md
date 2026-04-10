# | Assessment | Pipelines de CI/CD e DevOps |

### Diferença entre runners hospedados pelo GitHub e auto-hospedados, citando vantagens e desvantagens:

Os runners hospedados pelo GitHub são máquinas já preparadas pelo GitHub, que executam jobs no workflow.
Já runners auto-hospedados podem ser preparados e customizados pelo desenvolvedor no repositório (com uma máquina dedicada).

Os runners hospedad[gradle-ci.yml](.github/workflows/gradle-ci.yml)os pelo GitHub oferecem a facilidade e simplicidade de setup, com a desvantagem sendo a falta de flexibilidade e customização. 
Isso é diferente da maneira self-hosted, que te dá a liberdade de configurar um ambiente próprio e personalizado (hardware e software) para a execução dos workflows.
Porém, existe a desvantagem da complexidade e tempo gasto para preparar e manter todo esse ambiente.
