# Pensamento Computacional Aplicado
## Decomposição
Dividindo o sistema em partes menores (microserviços):

- Autenticação (login/cadastro)
- Catálogo de produtos
- Busca e recomendação
- Carrinho de compras
- Pedidos
- Pagamentos
- Envio/logística/rastreio
- Avaliações
- Notificações (email, SMS)
- Suporte ao cliente

## Reconhecimento de Padrões
Plataformas já existentes, como Amazon, Mercado Livre e Shopee, podem servir como referência, ajudando a projetar soluções baseadas nos padrões já testados.

Alguns dos padrões observados nesses sistemas são:
- Uso de microserviços
- Sistemas de recomendação personalizados
- Arquitetura baseada em nuvem
- Cache para melhorar desempenho
- Filas para processamento

## 3. Abstração

Foco no que é essencial:

Mais importante:

- Performance
- Segurança
- Escalabilidade
- Confiabilidade

Menos crítico (pode ser simplificado inicialmente):

- Personalização avançada
- Recursos estéticos complexos
- Funcionalidades secundárias (ex: redes sociais internas)

## 4. Algoritmos

Com base nos desafios e na estrutura definida, são apresentadas a seguir soluções para cada desafio.

**Escalabilidade:**
- Uso de balanceamento de carga em nuvem. Distribui tráfego de rede e cargas de trabalho entre vários servidores, evitando sobrecarga em um único ponto e garantindo alta escalabilidade e desempenho.
- Auto scaling (dimensionamento automático). Ajusta a quantidade de servidores baseando-se na demanda, aumentando recursos em períodos de pico e reduzindo quando a demanda é baixa.
 
**Desempenho:**
- Implementação de cache (ex: produtos mais acessados)
- Uso de CDN

**Segurança:**
- Criptografia de dados
- Autenticação em múltiplos fatores
- Monitoramento de fraudes

**Recomendação:**
- Algoritmos baseados em histórico de compras e navegação

**Confiabilidade:**
- Sistemas de backup
- Monitoramento em tempo real
