# LINUXtips-PICK

🚀 **Desafio de Projeto Prático - PICK 2024_01** 🚀

Bem-vindo ao repositório do meu projeto desenvolvido durante o curso PICK (Programa Intensivo Container e Kubernetes) da @LINUXtips. Este projeto tem como objetivo a criação de uma aplicação de gestão de senhas utilizando uma stack de tecnologias voltadas para segurança, automação e monitoramento contínuo.

## 📝 Descrição do Projeto

Este repositório contém a implementação de uma aplicação de gestão de senhas baseada no projeto **giropops-senhas**. O objetivo é aplicar e configurar as tecnologias Docker, Kubernetes, Helm, Kyverno, Cosign, Prometheus, apko e Melange para garantir altos padrões de segurança e automação.

## 🛠 Tecnologias Utilizadas

- **Docker**: Containerização da aplicação, com um Dockerfile eficiente e seguro. Imagens publicadas em repositórios privados.
- **Kubernetes**: Orquestração da aplicação com manifests (Deployment, Service, ConfigMap, Secret, etc.) e configuração de Ingress para exposição externa.
- **Helm**: Automação do deploy utilizando Helm, com charts customizados para diferentes ambientes (dev, staging, prod).
- **Kyverno**: Aplicação de políticas de segurança, incluindo verificação de imagens assinadas, proibição de execução como root e conformidade.
- **Cosign**: Assinatura e verificação de imagens Docker para aumentar a segurança.
- **Prometheus**: Implementação de métricas customizadas e configuração de alertas inteligentes.
- **APKO e Melange**: Criação e distribuição de pacotes da aplicação, utilizando pipelines CI/CD para ambientes diferentes.

## 🎯 Objetivo

Construir uma aplicação de gestão de senhas que atenda aos mais altos padrões de segurança, automação e monitoramento contínuo, utilizando as tecnologias mais recentes e eficientes no mercado de DevOps e infraestrutura.


## 📈 Monitoramento e Alertas

Configuração de Prometheus para coletar métricas customizadas da aplicação e configurar alertas baseados em condições específicas.

## 🔒 Segurança

Implementação de políticas Kyverno para assegurar boas práticas de segurança na aplicação e no cluster Kubernetes, além da assinatura de imagens com Cosign.

## 📜 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
