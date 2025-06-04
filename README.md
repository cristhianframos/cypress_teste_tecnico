# cypress_teste_tecnico

estes Capgemini

1 - Quantos testes serão necessários para validação dessa máquina e qual técnica a ser utilizada?

Resolução:

    - São 5 bandeiras: Visa, Master, Elo, Amex, Hiper
    - Cada bandeira possui 2 operações: débito e crédito
    
    Total de testes = 5 bandeiras x 2 operações = 10 testes
    
    Técnica a ser utilizada: Tabela de Decisão ou Matriz de Combinatória.Esta técnica é ideal para cenários onde temos diversas combinações de variáveis que influenciam o comportamento do sistema.

2 - Quais os testes deverão ser feitos desse range de bins para confirmar que está funcionando?

Resposta correta: 

    d) 232424, 232425, 232459, 232460, 232461
    Justificativa: Os testes devem incluir valores:
        - Abaixo do range (232424)
        - No limite inferior (232425)
        - Um valor intermediário (232459)
        - No limite superior (232460)
        - Acima do range (232461)
Técnica aplicada: Particionamento de Equivalência e Análise de Valor Limite.

3 - Cite uma abordagem de desenvolvimento ágil e explique-a!

    Resposta:
    Uma abordagem ágil bastante utilizada é o Scrum.
    crum é um framework que organiza o trabalho em ciclos curtos chamados sprints, geralmente de 1 a 4 semanas. Durante cada sprint, a equipe trabalha para entregar incrementos funcionais do produto. O Scrum valoriza a colaboração, adaptação constante e entregas frequentes.Os papéis principais são: Product Owner, Scrum Master e Development Team.

4 - O que é CI/CD?

Resposta:

    CI/CD significa Integração Contínua (Continuous Integration) e Entrega/Implantação Contínua (Continuous Delivery/Deployment).
    - CI: prática de integrar código de forma frequente, executando automaticamente builds e testes.
    - CD: prática de automatizar a entrega e/ou implantação do código em ambientes de homologação ou produção, garantindo agilidade e qualidade nas entregas.
    
    Benefícios: reduz erros, acelera entregas e melhora a colaboração entre as equipes.

5 - O que é TDD, BDD e ATDD e quando são aplicadas?

    - TDD (Test Driven Development): Desenvolvimento orientado a testes, onde os testes são criados antes do código. Foco na qualidade e design do código.
    - BDD (Behavior Driven Development): Desenvolvimento orientado ao comportamento do sistema. Usa linguagem natural (ex.: Gherkin) para descrever cenários e promover a colaboração entre áreas técnicas e de negócio.
    - ATDD (Acceptance Test Driven Development): Desenvolvimento orientado aos testes de aceitação. Define, junto ao cliente, os critérios de aceitação antes do desenvolvimento.
    - Quando são aplicadas: Em ambientes que priorizam qualidade, comunicação entre equipes e entregas com foco no valor para o cliente.

6 - Cite uma heurística de testes utilizada para testes de front e de back e explique-as:

    - Para Front-end:Heurística de Consistência e Padrão:Garante que elementos visuais, comportamentos e interações sigam o mesmo padrão em toda a aplicação, melhorando a experiência do usuário.

    - Para Back-end:Heurística CRUD:Testar as operações principais de um sistema: Create, Read, Update e Delete, garantindo a integridade e o funcionamento adequado das APIs ou banco de dados.

7 - Cite ferramentas de testes automatizados para:

    - Desktop: WinAppDriver, AutoIt, Winium
    - Web: Selenium, Cypress, Playwright
    - APIs: Postman, RestAssured, SoapUI
    - Mobile: Appium, Espresso (Android), XCUITest (iOS)
