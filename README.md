## Ferramentas Utilizadas
- **Gemini** (para geração de texto e imagem)

## Resultado

### Relato gerado
> Nem sempre um problema de internet está relacionado ao provedor.
>
> Hoje, me deparei com um cenário interessante na infraestrutura de rede: lentidão generalizada, perda de pacotes e falhas intermitentes no acesso aos sistemas internos. Iniciei a investigação com testes de ping, verificação do gateway e análise da utilização das interfaces dos switches. Após descartar uma falha no link de internet, identifiquei um volume excessivo de tráfego broadcast na rede. Analisando a topologia física e o comportamento das interfaces, cheguei à causa raiz: um loop de camada 2 provocado por uma conexão redundante entre switches.
>
> Após isolar a porta responsável, a rede voltou à normalidade. Realizei novos testes de conectividade e estabilidade, além de revisar as configurações do Spanning Tree e avaliar a implementação de mecanismos de proteção, como o BPDU Guard nas portas de acesso. Mais do que restabelecer a operação, o objetivo foi reduzir a possibilidade de reincidência. Resolver problemas de infraestrutura exige método, conhecimento técnico e, principalmente, entender a causa antes de aplicar uma solução.

### Imagem gerada
![Incidente de rede em infraestrutura](imagem-data-center.jpg)
