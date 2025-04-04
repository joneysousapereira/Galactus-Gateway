# Galactus-Gateway
Seus tickets encontram sua órbita perfeita!
## Mermaid
```mermaid
flowchart TB
    A[Novo Ticket Criado] --> B{Análise do Conteúdo}
    B -->|Usar IA/NLP| C[Modelo de IA Analisa Texto]
    B -->|Usar Regras Simples| D[Verificar Palavras-Chave]
    
    C --> E{Confiança da IA > 90%?}
    D --> F{Encontrou Palavra-Chave?}
    
    E -->|Sim| G[Classificação Automática: Categoria/Prioridade]
    E -->|Não| H[Encaminhar para Pool de Triagem Humana]
    F -->|Sim| G
    F -->|Não| H
    
    G --> I[Atribuir a Equipe Específica]
    H --> I
    
    I --> J[Ticket Classificado e Atribuído]

    subgraph IA
        C --> E
    end

    subgraph Automação
        D --> F
    end
```
