# Plano Orçamentário e Análise de Viabilidade de Rede Industrial  
## Indústria de Produção de Tijolos Ecológicos

---

## 1. Introdução

Este documento apresenta o planejamento para a implantação de uma rede industrial em uma indústria de produção de tijolos ecológicos. O objetivo é estruturar a infraestrutura de comunicação e automação, garantindo eficiência operacional, confiabilidade e possibilidade de expansão futura.

---

## 2. Levantamento Técnico de Equipamentos

A rede industrial será composta por dispositivos de automação, comunicação e supervisão.

### 2.1 Controladores e Automação

| Equipamento | Descrição | Especificação Técnica |
|------------|----------|----------------------|
| CLP (Controlador Lógico Programável) | Controle das máquinas de produção | Suporte a Modbus/TCP, entradas e saídas digitais/analógicas |
| IHM (Interface Homem-Máquina) | Interface de operação | Tela touchscreen, comunicação Ethernet |
| Sensores industriais | Monitoramento de processos | Sensores de temperatura, pressão e presença |

---

### 2.2 Rede Industrial

| Equipamento | Descrição | Especificação Técnica |
|------------|----------|----------------------|
| Switch industrial | Interligação da rede | Gerenciável, suporte a VLAN, resistente a ambiente industrial |
| Roteador industrial | Conexão com rede corporativa | VPN, firewall integrado |
| Cabeamento | Comunicação de dados | Cabo Ethernet Cat6 industrial |
| Rack industrial | Organização dos equipamentos | Proteção contra poeira e calor |

---

### 2.3 Sistema Supervisório

| Equipamento | Descrição | Especificação |
|------------|----------|--------------|
| Servidor SCADA | Supervisão e controle | Monitoramento em tempo real |
| Software SCADA | Interface de gestão | Integração com CLP e banco de dados |

---

## 3. Pesquisa de Fornecedores e Cotação

### 3.1 Fornecedores Sugeridos

- Siemens (CLPs e automação)
- Schneider Electric (switches e energia)
- WEG (equipamentos industriais)
- Intelbras (rede e comunicação)
- Altus (automação nacional)

---

### 3.2 Estimativa de Custos

| Equipamento | Quantidade | Valor Unitário (R$) | Total (R$) |
|------------|-----------|---------------------|------------|
| CLP | 2 | 4.500 | 9.000 |
| IHM | 2 | 2.500 | 5.000 |
| Switch industrial | 2 | 1.800 | 3.600 |
| Roteador industrial | 1 | 2.000 | 2.000 |
| Sensores | 10 | 150 | 1.500 |
| Cabeamento | - | 1.000 | 1.000 |
| Servidor SCADA | 1 | 6.000 | 6.000 |
| Software SCADA | 1 | 3.000 | 3.000 |

**Total estimado: R$ 31.100**

---

### 3.3 Prazos de Entrega

- Equipamentos nacionais: 5 a 10 dias úteis  
- Equipamentos importados: 15 a 30 dias  
- Implantação: 30 dias  

---

## 4. Adequação ao Ambiente Industrial

Os equipamentos selecionados atendem às exigências industriais:

- Resistência a poeira e altas temperaturas;
- Proteção contra interferência eletromagnética;
- Operação contínua (24/7);
- Certificações industriais (IP, IEC).

---

## 5. Escalabilidade e Integração

A solução proposta permite:

- Expansão da rede com novos dispositivos;
- Integração com sistemas ERP e MES;
- Comunicação via protocolos industriais (Modbus, OPC);
- Implementação futura de IoT industrial.

---

## 6. Análise de Viabilidade Técnica e Econômica

### 6.1 Viabilidade Técnica

A implantação é tecnicamente viável devido:

- Uso de tecnologias consolidadas;
- Compatibilidade entre equipamentos;
- Facilidade de manutenção;
- Integração com sistemas corporativos.

---

### 6.2 Viabilidade Econômica

#### Custo-benefício

- Redução de falhas operacionais;
- Aumento da produtividade;
- Diminuição de desperdícios;
- Melhor controle de processos.

---

### 6.3 Retorno sobre Investimento (ROI)

Estimativa:

- Redução de custos operacionais: ~20%
- Aumento de produtividade: ~15%
- Payback estimado: 12 a 18 meses

---

### 6.4 Riscos Envolvidos

- Dependência de fornecedores;
- Falhas na implementação;
- Necessidade de treinamento da equipe;
- Custos de manutenção.

---

## 7. Benefícios para o Negócio

- Automação do processo produtivo;
- Maior eficiência operacional;
- Tomada de decisão baseada em dados;
- Redução de custos;
- Melhoria na qualidade do produto.

---

## 8. Diagrama da Arquitetura da Rede
            [ Rede Corporativa / ERP ]
                     |
               [ Roteador ]
                     |
             [ Switch Industrial ]
               /        |        \
            /           |         \
        [CLP]        [CLP]     [Servidor SCADA]
         |             |
    [Sensores]    [Máquinas]
         |
      [IHM]


---

## 9. Conclusão

A implantação da rede industrial proposta apresenta alta viabilidade técnica e econômica, contribuindo significativamente para a modernização da indústria de tijolos ecológicos. A solução garante integração, escalabilidade e competitividade, alinhando a empresa aos conceitos da Indústria 4.0.