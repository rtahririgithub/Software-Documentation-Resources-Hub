# Software Documentation Guide

Great documentation is essential for any software project. It helps teams work together effectively and ensures everyone understands how to use and maintain the code. However, many teams struggle with documentation - it's often outdated, inconsistent, or missing entirely.
This guide provides everything you need to create and maintain excellent documentation:

- Templates and tools you can start using right away
- Best practices and standards to keep your docs consistent 
- Real examples from successful projects

## Contents

- [Documentation Types](#documentation-types)
  - [User Documentation](#user-documentation)
  - [Architectural Documentation](#architectural-documentation)
  - [API Documentation](#api-documentation)
  - [Code Documentation](#code-documentation)
  - [Test Documentation](#test-documentation)
  - [Other Types](#other-types)
- [General Tools](#general-tools)
  - [Site Builder](#site-builder)
  - [Wiki Builder](#wiki-builder)
  - [Knowledge Base](#knowledge-base)
  - [Checker & Formatter](#checker--formatter)
  - [Diagramming](#diagramming)
  - [Multimedia](#multimedia)
  - [Commercial](#commercial)
- [More Topics](#more-topics)
  - [Communities](#comunities)
  - [Examples](#examples)
  - [Formats](#formats)
  - [Guidelines](#guidelines)
  - [Books](#books)
  - [Courses](#courses)
  - [DocOps](#docops)
  - [Localization](#localization)
  - [Accessibility](#accessibility)

## Documentation Types

### User Documentation

> "Without good documentation, your users won't know how to use your product - no matter how great it is." - [The Documentation System](https://documentation.divio.com/introduction.html)

#### Tutorials
Tutorials walk users through specific tasks step-by-step. Key resources:

- [Tutorial writing guide](https://documentation.divio.com/tutorials.html) - Learn best practices from The Documentation System
- [Tutorial template](https://gitlab.com/tgdp/templates/-/blob/main/tutorial/template-tutorial.md) - Ready-to-use template from The Good Docs Project 
- [Writing effective tutorials](https://www.writethedocs.org/videos/portland/2021/writing-a-perfect-technical-tutorial-jessica-garson/) - Tips on creating and improving tutorials
- [Example: Astro Blog Tutorial](https://docs.astro.build/en/tutorial/0-introduction/) - See how Astro creates an engaging tutorial experience

#### Reference Documentation
Reference docs provide detailed information about features and functionality:

- [Writing reference guides](https://documentation.divio.com/reference.html) - Best practices for reference documentation
- [Reference template](https://gitlab.com/tgdp/templates/-/blob/main/reference/template-reference.md) - Start with this template from The Good Docs Project
- [SDK documentation tips](https://www.writethedocs.org/videos/portland/2019/sdk-reference-manuals-a-flow-based-approach-chris-bush/) - Creating user-friendly SDK documentation

#### How-to Guides
Step-by-step instructions for specific tasks:

- [How-to guide writing](https://documentation.divio.com/how-to-guides.html) - Learn to write clear how-to documentation
- [How-to template](https://gitlab.com/tgdp/templates/-/blob/main/how-to/template-how-to.md) - Ready-made template for how-to guides

#### Concept Documentation
Explanations of core ideas and theories:

- [Concept template](https://gitlab.com/tgdp/templates/-/blob/main/concept/template-concept.md) - Template for concept documentation
- [Writing explanations](https://documentation.divio.com/explanation.html) - Guide to explaining complex topics

#### FAQ Documentation
Common questions and answers:

- [Creating effective FAQs](https://www.writethedocs.org/videos/portland/2018/the-facts-about-faqs-ashleigh-rentz/) - Best practices for FAQ sections

#### In-app Documentation
Help text and guidance within applications:

- [Driver.js](https://github.com/kamranahmedse/driver.js) - Lightweight tool for creating user tours
- [Shepherd](https://github.com/shepherd-pro/shepherd) - Guide users through your application

#### Additional Resources
Other important documentation types:

- [Installation guide template](https://gitlab.com/tgdp/templates/-/blob/main/installation-guide/template-installation-guide.md)
- [Troubleshooting guide template](https://gitlab.com/tgdp/templates/-/tree/main/troubleshooting)
- [Terminology guide template](https://gitlab.com/tgdp/templates/-/blob/main/terminology-system/guide-terminology-system.md)
- [Release notes template](https://gitlab.com/tgdp/templates/-/blob/main/release-notes/template-release-notes.md)
- [Support documentation guide](https://www.writethedocs.org/videos/prague/2019/the-power-of-empathy-in-support-documentation-a-5-step-guide-plamena-maleva/)

### Architectural Documentation

> "Architecture is about the important stuff. Whatever that is." — Ralph Johnson

#### arc42 Framework
A comprehensive architecture documentation template:

- [arc42 website](https://arc42.org/) - Template and guidelines
- [Template downloads](https://arc42.org/download#format-overview) - Available in multiple formats
- [HTML Sanity Checker example](https://hsc.aim42.org/documentation/hsc_arc42)
- [Bike tracker example](https://biking.michael-simons.eu/docs/index.html)
- [arc42 + C4 example](https://github.com/bitsmuggler/arc42-c4-software-architecture-documentation-example)
- [docToolchain](https://github.com/doctoolchain/doctoolchainb)
- [Architecture documentation guide](https://www.workingsoftware.dev/software-architecture-documentation-the-ultimate-guide/)

#### C4 Model
System architecture visualization:

- [C4 model site](https://c4model.com)
- [draw.io plugin](https://github.com/tobiashochguertel/c4-draw.io)
- [PlantUML integration](https://github.com/plantuml-stdlib/C4-PlantUML)
- [Mermaid support](https://mermaid.js.org/syntax/c4.html)
- [Structurizr](https://github.com/structurizr)
- [C4-Builder](https://github.com/adrianvlupu/C4-Builder)
- [C4Sharp](https://github.com/8T4/c4sharp)
- [Goa Design Model](https://github.com/goadesign/model)

#### Additional Tools
- [Log4brains](https://github.com/thomvaill/log4brains) - Architecture Decision Records
- [Google Design Docs](https://www.industrialempathy.com/posts/design-docs-at-google/) - How Google handles design documentation

### API Documentation

> "All teams must expose their data and functionality through service interfaces." - [The Bezos API Mandate](https://nordicapis.com/the-bezos-api-mandate-amazons-manifesto-for-externalization/)

#### General API Tools
- [API reference template](https://gitlab.com/tgdp/templates/-/blob/main/api-reference/template-api-reference.md)
- [Slate](https://github.com/slatedocs/slate) - Beautiful API documentation
- [Widdershins](https://github.com/Mermade/widdershins) - Convert API definitions to markdown
- [DevDocs](https://github.com/freeCodeCamp/devdocs) - Combined API documentation browser
- [Zeal](https://github.com/zealdocs/zeal) - Offline documentation browser
- [apiDoc](https://github.com/apidoc/apidoc) - API documentation generator

#### OpenAPI Tools
For REST API documentation:

- [Swagger UI](https://github.com/swagger-api/swagger-ui)
- [Swagger Petstore demo](https://petstore3.swagger.io/)
- [Redoc](https://github.com/Redocly/redoc)
- [RapiDoc](https://github.com/rapi-doc/RapiDoc)
- [Fern](https://github.com/fern-api/fern)
- [Elements](https://github.com/stoplightio/elements)
- [Scalar](https://github.com/scalar/scalar)

#### GraphQL Documentation
- [GitHub GraphQL docs](https://docs.github.com/en/graphql)
- [SpectaQL](https://github.com/anvilco/spectaql)
- [GraphQLDocs](https://github.com/brettchalupa/graphql-docs)
- [Magidoc](https://github.com/magidoc-org/magidoc)

#### gRPC Documentation
- [protoc-gen-doc](https://github.com/pseudomuto/protoc-gen-doc)
- [Documentation example](https://rawgit.com/pseudomuto/protoc-gen-doc/master/examples/doc/example.html)
- [Sabledocs](https://github.com/markvincze/sabledocs)
- [Demo documentation](https://markvincze.github.io/sabledocs/demo/)

#### AsyncAPI Documentation
For event-driven APIs:

- [AsyncAPI Generator](https://github.com/asyncapi/generator)
- [AsyncAPI React](https://github.com/asyncapi/asyncapi-react)
- [Petstore Kafka example](https://github.com/swagger-api/petstore-kafka?tab=readme-ov-file#openapi-and-asyncapi)

#### RAML Documentation
- [API Console](https://github.com/mulesoft/api-console)
- [RAML to HTML](https://github.com/raml2html/raml2html)
- [Example documentation](https://rawgit.com/raml2html/default-theme/master/examples/world-music-api.html)

### Code Documentation

#### README Files
Essential project documentation:

- [README template](https://github.com/othneildrew/Best-README-Template)
- [Awesome README examples](https://github.com/matiassingers/awesome-readme)
- [Good Docs template](https://gitlab.com/tgdp/templates/-/blob/main/readme/template-readme.md)
- [readme.so editor](https://github.com/octokatherine/readme.so)

#### Code Comments
Best practices for code documentation:

- [Comment writing guide](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/)
- [Engineering guide to comments](https://stepsize.com/blog/the-engineers-guide-to-writing-code-comments)
- [NERD Commenter](https://github.com/preservim/nerdcommenter)

#### Error Messages
Creating helpful error documentation:

- [Writing error messages](https://www.writethedocs.org/videos/prague/2019/101-to-404s-how-to-write-great-error-messages-james-scott/)

#### Collaboration Documentation
Templates for team documentation:

- [Contributing guide](https://gitlab.com/tgdp/templates/-/blob/main/contributing-guide/template-contributing-guide.md)
- [Code of conduct](https://gitlab.com/tgdp/templates/-/tree/main/code-of-conduct)
- [Style guide](https://gitlab.com/tgdp/templates/-/blob/main/style-guide/template-style-guide.md)
- [License templates](https://github.com/licenses/license-templates)

#### Language-specific Documentation

JavaScript:
- [JSDoc](https://github.com/jsdoc/jsdoc)
- [documentation.js](https://github.com/documentationjs/documentation)
- [Docz](https://github.com/doczjs/docz)
- [Storybook](https://github.com/storybookjs/storybook)

TypeScript:
- [TSDoc](https://github.com/microsoft/tsdoc)

Python:
- [Docstring guide](https://peps.python.org/pep-0257/)
- [Google style guide](https://github.com/google/styleguide/blob/gh-pages/pyguide.md#38-comments-and-docstrings)
- [Python documentation guide](https://realpython.com/documenting-python-code/#commenting-vs-documenting-code)

PHP:
- [phpDocumentor](https://github.com/phpDocumentor/phpDocumentor)

C#:
- [Docfx](https://github.com/dotnet/docfx)

C++:
- [Doxygen](https://github.com/doxygen/doxygen)

Java:
- [JavaDoc overview](https://en.wikipedia.org/wiki/Javadoc)
- [Maven plugin](https://github.com/apache/maven-javadoc-plugin)
- [javadoc.io](https://javadoc.io/)

Kotlin:
- [Dokka](https://github.com/Kotlin/dokka)

Go:
- [Go Doc Comments](https://go.dev/doc/comment)
- [Swag](https://github.com/swaggo/swag)

Rust:
- [Rustdoc](https://doc.rust-lang.org/nightly/rustdoc/)
- [Docs.rs](https://github.com/rust-lang/docs.rs)

Ruby:
- [TomDoc](http://tomdoc.org/)

Perl:
- [perlpod](https://perldoc.perl.org/perlpod)

SQL:
- [SchemaSpy](https://github.com/schemaspy/schemaspy)

### Test Documentation

#### Test Plans
Templates and examples:

- [IEEE template](https://github.com/JennifferLockwood/test_plan_template)
- [SONiC template](https://github.com/sonic-net/SONiC/blob/master/doc/SONiC%20Test%20Plan%20Template.md)
- [VS Code guide](https://github.com/microsoft/vscode/wiki/Writing-Test-Plan-Items)
- [Performance template](https://www.perfmatrix.com/performance-test-plan-document-template/)

#### Test Cases
Resources for writing test cases:

- [Manual testing examples](https://github.com/mfaisalkhatri/Manual_Testing)
- [Guru99 template](https://www.guru99.com/download-sample-test-case-template-with-explanation-of-important-fields.html)
- [Katalon template](https://katalon.com/resources-center/blog/test-case-template-examples)

#### Test Reports
Documentation for test results:

- [Bug report template](https://gitlab.com/tgdp/templates/-/blob/main/bug-report/template-bug-report.md)
- [Performance report template](https://www.perfmatrix.com/performance-test-report-template/)
- [Results report guide](https://u-tor.com/topic/performance-testing-report)
- [Summary report guide](https://www.linkedin.com/pulse/step-by-step-guide-creating-powerful-performance-summary-james-ohia/)

### Other Documentation Types

#### Project Requirements Documentation
Templates and resources:

- [Notion templates](https://www.notion.so/templates/category/product-requirements-doc)
- [Product School templates](https://productschool.com/blog/product-strategy/product-template-requirements-document-prd)
- [Aha! templates](https://www.aha.io/roadmapping/guide/requirements-management/what-is-a-good-product-requirements-document-template)

#### Request for Comment (RFC)
- [RFC template](https://gitlab.com/tgdp/request-for-comment/-/blob/main/rfc-template.md)

## General Tools

### Site Builders
Documentation website generators:

- [Docusaurus](https://github.com/facebook/docusaurus)
- [Docsify](https://docsify.js.org/#/)