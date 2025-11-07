# spec-kit-prompt
```sh
uvx --from git+https://github.com/github/spec-kit.git specify init podsite
```

```md
 Translate the generated Markdown into Traditional Chinese and save it as a new file.
```

```md
/speckit.constitution Fill the constitution with the bare minimum requirements for a static web app based on the template. 
```

```md
/speckit.specify I am building a modern podcast website. I want it to look sleek, professional, and stand out. Should have a landing page with one featured episode. There should be an episodes page, an about page, and a FAQ page. Should have 20 episodes, and the data is mocked - you do not need to pull anything from any real feed.
```

```md
For things that need clarification, use the best guess you think is reasonable. Update acceptance checklist after.
```

```md
/speckit.plan I am going to use Next.js with static site configuration, no databases - data is embedded in the content for the mock episodes. Site is responsive and ready for mobile.
```

```md
/speckit.plan I'm going to use Java EE 8.The relevant technology stack is as follows:
# Core Technology Stack
1. Java Platform
- Java Version: Java 8 (JDK 1.8)
- Encoding Standard: UTF-8
- Build Tool: Apache Maven 3.x
2. Application Server
- Server: WildFly 26.1.3.Final
- Specification: Java EE 8
- Deployment Format: WAR (Web Application Archive)
- Containerization: Docker-based deployment
3. Web Framework
- JSF: JavaServer Faces 2.3
- PrimeFaces: Enterprise-grade JSF component library
- PrimeFaces Extensions: Extended components
- Font Awesome: Icon library
- CKEditor: Rich text editor
4. Enterprise Technologies
- CDI: Jakarta Context and Dependency Injection
- EJB: Enterprise Java Beans 3.2
- JPA: Jakarta Persistence API
- JTA: Java Transaction API
- Bean Validation: Jakarta Validation API
5. Persistence Layer
- ORM: Hibernate (EntityManager)
- Database: Oracle Database
- Dialect: Oracle10gDialect (customized)
- Data Source: JTA-managed data source
6. Web Services
- SOAP: JAX-WS (SOAP Web Services)
- REST: JAX-RS (RESTful Services)
- JSON: Google Gson
- XML: JAXB, XStream, Apache XMLBeans
7. Security and Authentication
- SAML 2.0: Single Sign-On (SSO)
- Azure AD: Microsoft MSAL4J
- JWT: Nimbus JOSE JWT
- Microsoft Graph: Graph SDK
8. Reporting and Document Processing
- Reporting Engine: JasperReports
- Excel: Apache POI
- PDF: Apache PDFBox
- Template Engine: FreeMarker
9. Utility Libraries
- Apache Commons: Lang, Lang3, Net, FileUpload
- HTTP Client: Apache HttpComponents Client5
- SSH: JSch (com.github.mwiede)
- XML Processing: Dom4j
- Scripting Engine: Groovy 2.5.8
10. Testing Frameworks
- Unit Testing: JUnit
# Development Standards
## Code Structure
- Presentation Layer: JSF XHTML + PrimeFaces components
- Controller Layer: CDI Managed Beans
- Business Layer: EJB Session Beans
- Service Layer: REST/SOAP Web Services
- Persistence Layer: JPA Entities + DAO
- Data Layer: Oracle Database

# Development Guidelines
## When working on the AGBS project, please:
1. Follow Java EE 8 specifications
2. Use CDI for dependency injection instead of directly instantiating objects
3. Use EJB for business logic and transaction management
4. Use JPA for database operations, avoiding direct JDBC
5. Use JSF + PrimeFaces for the frontend, avoiding other JS frameworks
6. Follow a layered architecture to maintain separation of concerns
7. Use JTA for distributed transaction management
8. Implement proper exception handling and logging
9. Design APIs following RESTful principles
10. Ensure code supports internationalization and localization
# Common Task Examples
## Creating a New JSF Page
- Use XHTML + JSF 2.3 tags
- Integrate PrimeFaces components
- Bind to CDI Managed Beans
- Implement form validation
## Developing Business Logic
- Create EJB Session Beans
- Inject dependencies using CDI
- Implement transaction management
- Integrate JPA for data access
## Building REST APIs
- Use JAX-RS annotations
- Implement JSON serialization
- Handle exceptions and error responses
- Integrate security authentication
## Database Operations
- Use JPA EntityManager
- Write JPQL queries
- Implement pagination and sorting
- Handle lazy loading
# Notes
- This project runs on WildFly 25.0.1, ensure compatibility
- Use Java 8 syntax, avoid Java 9+ features
- The frontend must use JSF + PrimeFaces, avoid Angular/React/Vue
- The database is Oracle, be mindful of SQL dialect differences
- The project uses SAML 2.0 for Single Sign-On
- All code must use UTF-8 encoding
- Follow the existing project structure and naming conventions
```

```md
/speckit.tasks break this down into tasks.
```

```md
Implement the tasks for this project, and update the task list as you go.
```
