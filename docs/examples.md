# 🎨 Real-World Examples & Templates

See the Codebase Interface principles in action! From minimal services to complex applications, these examples show how to create welcoming, well-organized codebases that serve all audiences.

> 💡 **Copy & Adapt:** These aren't just examples - they're **production-ready templates** you can copy and customize for your own projects.

---

## 🚀 Quick Start Templates

Choose the template that matches your project type:

### 🏗️ Minimal Service
**Perfect for microservices, libraries, or small tools**
🔗 [View Template](#minimal-services)

### 📚 Documentation Site
**For open source projects with extensive documentation**
🔗 [View Template](#open-source-documentation-services)

### ⚡ Full-Stack Application
**Complete applications with frontend, backend, and infrastructure**
🔗 [View Template](#source-aligned-services)

---

## 🏗️ Minimal Services

**Perfect for:** Microservices, CLI tools, libraries, small utilities

### 🎯 **The Philosophy**

Keep it simple but complete. Every file has a clear purpose, and new developers can understand the entire project in minutes.

### ✨ **Perfect for teams that want:**

- Quick onboarding for small projects
- Consistent structure across microservices  
- Minimal overhead with maximum clarity
- Easy maintenance and updates

??? example "📁 **Complete Directory Structure**"
    ```txt
    my-awesome-service/
    ├── 📚 README.md                   # 👤 Users: What this service does & how to use it
    ├── 🤝 CONTRIBUTING.md             # 🧑‍💻 Contributors: How to help improve this service  
    ├── 🤖 AGENTS.md                   # 🤖 AI: Context for AI-assisted development
    ├── 🚀 RUNBOOK.md                  # 🛠️ Operators: How to deploy & maintain this service
    ├── 💬 SUPPORT.md                  # 🆘 All: How to get help when things go wrong
    ├── 📋 Taskfile.yml                # ⚙️ Build: Standardized commands for all tasks
    ├── 🎯 .editorconfig               # 📝 All: Consistent coding style across editors
    ├── 🚫 .gitignore                  # 📂 Git: What files to ignore in version control
    ├── 📏 .gitattributes              # 📂 Git: How to handle different file types
    ├── 📝 PULL_REQUEST_TEMPLATE.md    # 🔄 Process: Template for consistent PRs
    └── 📦 src/                        # 💻 Your actual service code goes here
        └── ...
    ```

??? example "🌟 **README.md Template**"
    ```markdown
    # 🚀 My Awesome Service

    > A brief, compelling description of what this service does and why it matters.

    [![Codebase Interface](https://img.shields.io/badge/Codebase_Interface-Principles-4b9ce2?style=flat-square)](https://codebaseinterface.org)
    [![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)](#)

    ## 🎯 What It Does

    **Problem:** What specific problem does this solve?
    **Solution:** How does your service solve it?
    **Benefit:** Why is this better than alternatives?

    ## ⚡ Quick Start

    ```bash
    # Install
    task install

    # Run
    task start

    # Test  
    task test
    ```

    ## 📚 Documentation

    - [🤝 Contributing](CONTRIBUTING.md) - How to help improve this service
    - [🚀 Deployment](RUNBOOK.md) - How to deploy and operate
    - [💬 Support](SUPPORT.md) - Get help when you need it

    ## 📄 License

    [Your License Here]
    ```

---

## 📚 Open Source Documentation Services

**Perfect for:** Open source projects, documentation sites, community-driven initiatives

<!-- markdownlint-disable MD033 -->
<div style="background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%); padding: 2rem; border-radius: 10px; margin: 1rem 0;">

### 🌟 **The Community-First Approach**
Built for maximum transparency and community engagement. Every audience has clear entry points and comprehensive resources.

### ✨ **Perfect for teams that want:**
- Strong community engagement
- Comprehensive documentation
- Clear governance and contribution processes
- Professional, welcoming presentation

</div>
<!-- markdownlint-enable MD033 -->

??? example "📁 **Complete Directory Structure**"
    ```txt
    awesome-documentation-project/
    ├── 📚 README.md                   # 👤 Project overview and navigation hub
    ├── 🤝 CONTRIBUTING.md             # 🧑‍💻 Detailed contribution guidelines
    ├── 📖 CODE_OF_CONDUCT.md          # 🌐 Community standards and behavior
    ├── 🔒 SECURITY.md                 # 🛡️ Security policy and reporting
    ├── 💬 SUPPORT.md                  # 🆘 Community support channels
    ├── 📝 LANGUAGE.md                 # 📚 Ubiquitous language definitions
    ├── 📋 TODO.md                     # 📝 Public roadmap and task tracking
    ├── 🤖 AGENTS.md                   # 🤖 AI agent documentation
    ├── 🚀 RUNBOOK.md                  # 🛠️ Operations and maintenance
    ├── 📄 LICENSE.md                  # ⚖️ Legal license information
    ├── 📈 CHANGELOG.md                # 📊 Version history and changes
    ├── 🔄 PULL_REQUEST_TEMPLATE.md    # 📝 PR template for consistency
    ├── 📋 Taskfile.yml                # ⚙️ Build and task automation
    ├── 📊 cliff.toml                  # 🛠️ Changelog generation config
    ├── 📚 mkdocs.yml                  # 📖 Documentation site configuration
    ├── 🌐 docs/                       # 📚 Comprehensive documentation
    │   ├── 🏠 README.md               # Documentation homepage
    │   ├── 🎯 principles.md           # Core principles and philosophy
    │   ├── 👥 audiences.md            # Audience definitions
    │   ├── 🔗 interfaces.md           # Interface specifications
    │   ├── 🏆 benefits.md             # Value proposition
    │   ├── 🎨 examples.md             # Real-world examples
    │   ├── 🛠️ tooling.md              # Recommended tools
    │   └── 🤝 Contribute.md           # Contribution guide
    ├── 🎯 .editorconfig               # 📝 Editor configuration
    ├── 🚫 .gitignore                  # 📂 Git ignore patterns  
    └── 📏 .gitattributes              # 📂 Git file handling rules
    ```

??? example "🎯 **Advanced README.md Template**"
    ```markdown
    # 🌟 Awesome Documentation Project

    > Transforming how teams create and maintain documentation that actually helps people.

    [![Codebase Interface](https://img.shields.io/badge/Codebase_Interface-Principles-4b9ce2?style=flat-square)](https://codebaseinterface.org)
    [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=flat-square)](https://conventionalcommits.org)
    [![Contributors](https://img.shields.io/github/contributors/username/repo?style=flat-square)](#)
    [![Stars](https://img.shields.io/github/stars/username/repo?style=social)](https://github.com/username/repo)

    ## 🎯 Mission

    **Vision:** Every developer deserves documentation that delights rather than frustrates.
    **Mission:** Provide tools and principles for creating world-class developer experiences.

    ## 🚀 Quick Experience

    ```bash
    # Get started in 30 seconds
    task setup    # Install everything you need
    task docs     # Launch live documentation
    task example  # See it in action
    ```

    **[📖 Read the Docs →](docs/README.md)** | **[🤝 Join Community →](#community)** | **[🎨 See Examples →](docs/examples.md)**

    ## 🌍 Community

    <table>
    <tr>
    <td align="center"><strong>💬 Discussions</strong><br><a href="#">Join conversations</a></td>
    <td align="center"><strong>🐛 Issues</strong><br><a href="#">Report bugs & request features</a></td>
    <td align="center"><strong>🔄 PRs</strong><br><a href="#">Contribute improvements</a></td>
    </tr>
    </table>

    ## 📋 Navigation

    | For | Document | Purpose |
    |-----|----------|---------|
    | 👤 **Users** | [📚 Docs](docs/README.md) | Learn the principles and see examples |
    | 🧑‍💻 **Contributors** | [🤝 Contributing](CONTRIBUTING.md) | Understand how to help |
    | 🛠️ **Operators** | [🚀 Runbook](RUNBOOK.md) | Deploy and maintain |
    | 🤖 **AI Agents** | [🤖 Agents](AGENTS.md) | Context for AI assistance |

    ## 📊 Project Status

    - ✅ Core principles documented
    - ✅ Example implementations available  
    - ✅ Community guidelines established
    - 🚧 Advanced tooling (in progress)
    - 📅 v2.0 roadmap (see [TODO.md](TODO.md))

    ---

    <div align="center">

    **Built with ❤️ by the community**

    [⭐ Star us](https://github.com/username/repo) • [🐦 Follow updates](#) • [💬 Join discussions](#)

    </div>
    ```

---

## ⚡ Source-Aligned Services  

**Perfect for:** Complex applications, enterprise services, full-stack systems

<!-- markdownlint-disable MD033 -->
<div style="background: linear-gradient(135deg, #f3e5f5 0%, #e1bee7 100%); padding: 2rem; border-radius: 10px; margin: 1rem 0;">

### 🏗️ **The Enterprise Architecture**
Designed for complex, business-critical applications with multiple teams and sophisticated requirements.

### ✨ **Perfect for teams that want:**
- Clear separation of concerns
- Scalable architecture patterns  
- Enterprise-grade documentation
- Team autonomy with consistency

</div>
<!-- markdownlint-enable MD033 -->

??? example "📁 **Complete Directory Structure**"
    ```txt
    enterprise-application/
    ├── 📚 Interface Layer (Codebase Interface)
    │   ├── 📖 README.md               # 👤 Application overview and value prop
    │   ├── 🤝 CONTRIBUTING.md         # 🧑‍💻 How to contribute across all domains
    │   ├── 🚀 RUNBOOK.md              # 🛠️ Operations across all environments
    │   ├── 🤖 AGENTS.md               # 🤖 AI context for the entire application
    │   ├── 💬 SUPPORT.md              # 🆘 Support escalation and contact info
    │   ├── 📝 LANGUAGE.md             # 📚 Business domain language
    │   ├── 📋 TODO.md                 # 📝 Cross-cutting tasks and roadmap
    │   ├── 📈 CHANGELOG.md            # 📊 Application-level changes
    │   ├── 📄 LICENSE.md              # ⚖️ Legal and licensing
    │   ├── 🔒 SECURITY.md             # 🛡️ Security policies
    │   └── 📋 Taskfile.yml            # ⚙️ Global build and deployment
    │
    ├── 🎨 design/                     # 📐 Architecture & Design Decisions  
    │   ├── 📖 README.md               # Introduction to design philosophy
    │   ├── 📋 contracts/              # API contracts, schemas, interfaces
    │   │   ├── api-v1.yaml            # OpenAPI specifications
    │   │   └── events.yaml            # AsyncAPI event definitions
    │   └── 🏛️ decisions/              # Architecture Decision Records (ADRs)
    │       ├── 001-microservices.md   # Why we chose microservices
    │       └── 002-event-sourcing.md  # Event sourcing decision
    │
    ├── 🧠 behaviour/                  # 💼 Business Logic & Domain Services
    │   ├── 📖 README.md               # Business domain introduction
    │   ├── 🛒 order-service/          # Order management domain
    │   ├── 👤 user-service/           # User management domain  
    │   ├── 💰 payment-service/        # Payment processing domain
    │   └── 📧 notification-service/   # Communication domain
    │
    ├── 🎭 experiences/                # 🎨 User Interfaces & Client Apps
    │   ├── 📖 README.md               # UI/UX philosophy and standards
    │   ├── 🌐 web-app/                # React/Vue/Angular web application
    │   ├── 📱 mobile-app/             # React Native/Flutter mobile app
    │   ├── 🤖 ai-chat/                # Conversational AI interface
    │   └── 🔌 api-gateway/            # External API interface
    │
    ├── 📡 publication/                # 📤 Data Publishing & Integration
    │   ├── 📖 README.md               # Data architecture overview
    │   ├── 🌊 event-streams/          # Kafka/Event streaming
    │   ├── 📊 data-warehouse/         # Analytics data pipeline
    │   ├── 🔗 integrations/           # Third-party integrations
    │   └── 📈 metrics/                # Application metrics & monitoring
    │
    └── 📊 outcomes/                   # 📈 Analytics, Reports & Intelligence
        ├── 📖 README.md               # Business intelligence overview
        ├── 📊 dashboards/             # Business intelligence dashboards  
        ├── 📈 reports/                # Automated reporting systems
        ├── 🤖 ml-models/              # Machine learning models
        └── 🔍 insights/               # Data science and insights
    ```

??? example "🎯 **Enterprise README.md Template**"
    ```markdown
    # 🏢 Enterprise Application Platform

    > A comprehensive platform delivering exceptional customer experiences through modern architecture and practices.

    [![Codebase Interface](https://img.shields.io/badge/Codebase_Interface-Principles-4b9ce2?style=for-the-badge)](https://codebaseinterface.org)
    [![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)](#)
    [![Security Score](https://img.shields.io/badge/security-A+-success?style=for-the-badge)](#)

    ## 🎯 Platform Overview

    **Mission:** Transform how customers interact with our services through innovative technology.

    **Architecture:** Event-driven microservices with domain-driven design principles.

    **Scale:** Serving 10M+ users across 50+ countries with 99.9% uptime.

    ## 🚀 Quick Start by Role

    <table>
    <tr>
    <td><strong>👤 Business Users</strong><br>
    <a href="#business-value">View Business Value</a><br>
    <a href="experiences/README.md">Access Applications</a>
    </td>
    <td><strong>🧑‍💻 Developers</strong><br>
    <a href="CONTRIBUTING.md">Start Contributing</a><br>
    <a href="design/README.md">Review Architecture</a>
    </td>
    <td><strong>🛠️ Operators</strong><br>
    <a href="RUNBOOK.md">Operations Guide</a><br>
    <a href="publication/metrics/">View Dashboards</a>
    </td>
    </tr>
    </table>

    ## 🏗️ Platform Architecture

    ```mermaid
    graph TB
        subgraph "🎭 Experiences"
            WEB[🌐 Web App]
            MOBILE[📱 Mobile App]
            API[🔌 API Gateway]
        end
        
        subgraph "🧠 Business Logic"
            ORDER[🛒 Orders]
            USER[👤 Users]
            PAYMENT[💰 Payments]
        end
        
        subgraph "📡 Data & Events"
            STREAM[🌊 Event Streams]
            DB[(📊 Database)]
            WAREHOUSE[(📈 Warehouse)]
        end
        
        WEB --> API
        MOBILE --> API
        API --> ORDER
        API --> USER
        API --> PAYMENT
        ORDER --> STREAM
        STREAM --> WAREHOUSE
    ```

    ## 📋 Domain Navigation

    | Domain | Purpose | Team | Documentation |
    |---------|---------|------|---------------|
    | 🧠 **[Behaviour](behaviour/README.md)** | Business logic & domain services | Backend Teams | Domain guides, APIs |
    | 🎭 **[Experiences](experiences/README.md)** | User interfaces & interactions | Frontend Teams | UI guides, components |
    | 📡 **[Publication](publication/README.md)** | Data integration & events | Platform Team | Data flows, schemas |
    | 📊 **[Outcomes](outcomes/README.md)** | Analytics & intelligence | Data Team | Reports, insights |
    | 🎨 **[Design](design/README.md)** | Architecture & decisions | Architecture Team | ADRs, contracts |

    ## 💼 Business Value

    - 🚀 **50% faster** feature delivery through domain separation
    - 📈 **300% increase** in developer productivity  
    - 🛡️ **99.9% uptime** with robust monitoring and automation
    - 🌍 **Global scale** serving millions of users seamlessly

    ## 🛠️ Development Workflow

    ```bash
    # Setup entire platform
    task setup

    # Start all services locally  
    task dev

    # Run comprehensive tests
    task test

    # Deploy to staging
    task deploy:staging

    # Deploy to production (with approvals)
    task deploy:production
    ```

    ## 📞 Support & Escalation

    - 🚨 **P0/P1 Issues:** [On-call rotation](RUNBOOK.md#on-call)
    - 💬 **Development Questions:** [Slack #platform-help](#)
    - 🐛 **Bug Reports:** [GitHub Issues](#)
    - 🚀 **Feature Requests:** [Product Board](#)

    ---

    <div align="center">

    **🎯 Built for Scale • 🚀 Optimized for Speed • 🛡️ Secured by Design**

    [📊 View Metrics](#) • [📖 Read Docs](design/README.md) • [🤝 Join Team](CONTRIBUTING.md)

    </div>
    ```

---

## 🎯 Implementation Checklist

Ready to transform your own codebase? Use this checklist:

### ✅ **Phase 1: Foundation (30 minutes)**

- [ ] Create compelling README.md with clear value proposition
- [ ] Add basic Taskfile.yml with setup/start/test commands  
- [ ] Include .editorconfig for consistent formatting
- [ ] Set up .gitignore and .gitattributes

### ✅ **Phase 2: Audience Interfaces (1 hour)**

- [ ] Write CONTRIBUTING.md for developers
- [ ] Create RUNBOOK.md for operators  
- [ ] Add AGENTS.md for AI context
- [ ] Include SUPPORT.md for help channels

### ✅ **Phase 3: Polish (30 minutes)**

- [ ] Add Codebase Interface badge to README
- [ ] Create pull request template
- [ ] Set up changelog generation
- [ ] Review and refine all documentation

### ✅ **Phase 4: Measurement (ongoing)**

- [ ] Track onboarding time improvements
- [ ] Measure contributor engagement
- [ ] Monitor support ticket reduction
- [ ] Collect feedback and iterate

## 🎊 Ready to Transform Your Codebase?

Pick a template above and start creating amazing experiences for all your audiences!

<!-- markdownlint-disable MD033 -->
<div class="navigation-buttons" markdown="1" style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-top: 1.5rem;">

<div markdown="1">
[← Previous: Tooling](../tooling/){ .md-button }
</div>

<div markdown="1" style="text-align: right;">
[Next: Welcome →](../){ .md-button .md-button--primary }
</div>

</div>

<style>
@media (max-width: 768px) {
  .navigation-buttons {
    display: grid !important;
    grid-template-columns: 1fr !important;
    gap: 0.5rem !important;
  }
  .navigation-buttons > div:last-child {
    text-align: left !important;
  }
}
</style>
<!-- markdownlint-enable MD033 -->
