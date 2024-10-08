# resumo-do-lab-az900
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO sobre AZ-900

# Microsoft Azure - Localizando Serviços por Categoria
Nessa aula aprendemos:
* Como mudar idioma do portal do Azure
* Mudar o tema do portal do Azure
* Como visualizar os recursos do Azure por Categoria.

Na Categoria - Rede
* Bastions - rede segura funciona como um Jump Server
* Firewall
* Armazenamento - Migração

* Quando constar como Versão Prévia (não é recomendado usar em base de produção)

# Benefícios da Nuvem Azure
* Alta disponibilidade
	* Uptime.: 99%, 99.9%, 99.95% ou 99.99% - SLA
* Escalabilidade e Elasticidade
	* Escalabilidade: vertical (aumenta os  recursos da maquina/container)
	* Elasticidade: horizontal (aumenta a quantidade de maquinas/containers)
* Confiabilidade, Previsibilidade e Segurança
	* Confiabilidade ligado a resiliência?
	* Cloud conta com design descentralizado
	* Previsibilidade em desempenho e custo
	* Segurança tem responsabilidade compartilhada
	* Azure oferece ferramentas de segurança, mas devem ser implementadas pelo cliente
* Governança e Gerenciabilidade
	* Importante estabelecer uma governança
	* Criação de regras de governança
	* Facilidade de gerenciamento de recursos através de várias formas (Portal, Linha de comando, APIs, Terraform, etc...)

# Criando máquinas Virtuais na Azure
* SLA
	* 99% (Tempo de inatividade por semana: 1,68 hora)
	* 99,9% (Tempo de inatividade por semana: 10,1 minutos)
	* 99,95% (Tempo de inatividade por semana: 5 minutos)
	* 99,99% (Tempo de inatividade por semana: 1,01 minuto)
	* 99,999% (Tempo de inatividade por semana: 6 segundos)
* Opções de disponibilidade
	* Sem redundância
	* Zona de disponibilidade
	* Conjunto de dimensioamento de maquinas virtuais
	* Conjunto de disponibilidade
* Sotorage também pode ter redundância

# Tipos de Serviço de Nuvem na Azure
* IaaS, PaaS e SaaS na Azure
	* IaaS: Infrastructure as a Service
		* O cliente controla, mantem e gerencia a infraestrutura
	* PaaS: Plataform as a Service
		* O cliente não se preocupa com a infraeturua, apenas com configuração da plataforma escolhida
	* SaaS: Software as a Service
		* É uma aplicação final disponibilizada para o usuário (Ex.: Office 365, Teams, etc...)
	
* Modelo de Responsabilidade Compartilhada
	* ![Modelo de Responsabilidade Compartilhada](https://learn.microsoft.com/pt-br/azure/security/fundamentals/media/shared-responsibility/shared-responsibility.svg)

# Configurando uma instância de Banco de Dados na Azure
* Necessário a criação de servidor com localização do mesmo
* Selecionar modelo de redundância
