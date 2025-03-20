# resumo2-do-lab-Criando-maquinas-virtuais-na-Azure
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO - Criando máquinas virtuais na Azure".

Benefícios da nuvem

⦁	Alta disponibilidade 
A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer. O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).
"Um Acordo de Nível de Serviço (SLA) é um contrato formal entre um provedor de serviços e seu cliente que define os parâmetros de qualidade e desempenho esperados para o serviço oferecido. O SLA especifica em detalhes os níveis de serviço acordados, incluindo disponibilidade, tempos de resposta, suporte técnico, entre outros. Seu objetivo é garantir a transparência e o compromisso com a qualidade, alinhando expectativas entre as partes envolvidas". Fonte: https://www.agenciacnow.com/acordo-de-nivel-de-servico-sla/
⦁	Escalabilidade
A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
A escala geralmente vem em duas variedades: vertical (escalabilidade) e horizontal (Elasticidade). A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos. A escala horizontal é adição ou subtração do número de recursos, ex.:adicionar mais CPUs ou RAM à máquina virtual.  Com a escala horizontal, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).Ex.: Balck friday
⦁	Confiabilidade
Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando. Ela também é um dos pilares do Microsoft Azure Well-Architected Framework.
Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Com recursos implantados em várias regiões do mundo, essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. Você pode criar aplicativos para aproveitar automaticamente essa confiabilidade maior. Em alguns casos, o próprio ambiente de nuvem mudará automaticamente para uma região diferente, sem que você precise realizar nenhuma ação. 
⦁	Previsibilidade
 A previsibilidade pode se concentrar na previsibilidade de desempenho (Dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho. EX.: se o tráfego estiver bem concentrado em uma área, o balanceamento de carga ajudará a redirecionar parte da sobrecarga para áreas menos sobrecarregadas) ou na previsibilidade de custo (A previsibilidade de custos se concentra em prever o custo dos gastos com a nuvem. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem). Tanto a previsibilidade de desempenho quanto a de custo são bastante influenciadas pelo Microsoft Azure Well-Architected Framework. 
⦁	Governança
Se você estiver implantando infraestrutura como serviço ou software como serviço, os recursos de nuvem vão dar suporte à governança e à conformidade. Itens como modelos de conjunto ajudam a garantir que todos os seus recursos implantados atendam aos padrões corporativos e aos requisitos regulatórios governamentais. Além disso, você pode atualizar todos os seus recursos implantados com novos padrões à medida que os padrões são alterados. A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
⦁	Segurança
Em relação à segurança, você pode encontrar uma solução de nuvem que atenda às suas necessidades de segurança. Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
E como a nuvem se destina a uma entrega de recursos de TI via Internet, os provedores de nuvem normalmente são adequados para lidar com situações como ataques de DDoS (negação de serviço distribuído), tornando sua rede mais robusta e segura.

⦁	Capacidade de gerenciamento na nuvem
O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:
⦁	Escalar automaticamente a implantação de recursos com base na necessidade.
⦁	Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
⦁	Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
⦁	Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.
⦁	Gerenciamento na nuvem
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Você pode gerenciá-los:
⦁	Por meio de um portal da Web.(Pré configurado)
⦁	Usando uma interface de linha de comando.(Manual)
⦁	Usando APIs.
⦁	Usando o PowerShell.

Fonte: https://learn.microsoft.com/pt-br/training/modules/describe-benefits-use-cloud-services/2-high-availability-scalability-cloud
