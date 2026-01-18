# 🤖 AI-Autonomous Testing Suite
**Powered by AutoGen Multi-Agent System + OpenAI**

> **Connect your GitHub repository, and watch AI agents autonomously analyze your codebase, generate comprehensive test suites, execute them safely, and provide actionable insights—all in one seamless workflow.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-blue.svg)](https://www.typescriptlang.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109-green.svg)](https://fastapi.tiangolo.com/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

AI-Autonomous Testing Suite is an intelligent quality engineering platform that uses a **two-agent AutoGen workflow** to:

1. **Analyze Your Codebase** — Deep code analysis using GPT-4.1-mini to understand structure, patterns, and critical paths
2. **Generate Test Plans** — AI proposes comprehensive test strategies tailored to your repository
3. **Create Test Suites** — Automatically generates unit and e2e tests following best practices
4. **Execute Safely** — Runs tests in a sandboxed environment with allowlisted commands
5. **Analyze Failures** — Provides detailed failure analysis with suggested code fixes and patches
6. **Track Performance** — Real-time analytics and insights on test runs and success rates

All orchestrated through a beautiful, state-driven interface with real-time updates—no page reloads required.

---

## 🎯 Core Features

### 🤖 **AI-Powered Test Generation**
- **Multi-Agent System** — DevAgent and ReviewerAgent work in tandem for quality assurance
- **Real OpenAI Integration** — GPT-4.1-mini for intelligent code analysis and test generation
- **Context-Aware Analysis** — Understands your codebase structure, patterns, and dependencies
- **Iterative Refinement** — Agents review and improve tests through multiple rounds
- **Smart Test Planning** — Prioritizes critical paths and edge cases automatically

### 📊 **Code Analysis & Quality Engineering**
- **Repository Analysis** — Deep inspection of code structure, imports, and dependencies
- **Test Coverage Insights** — Identifies gaps and suggests comprehensive test strategies
- **Failure Analysis** — Detailed breakdown of test failures with root cause identification
- **Patch Generation** — AI-suggested code fixes as review-ready diffs
- **Comparison Tools** — Side-by-side run comparison to track improvements over time

### 🔄 **CI/CD Integration**
- **GitHub OAuth** — Seamless repository connection with secure token management
- **Automated Workflows** — Trigger test runs directly from connected repositories
- **Job Queue System** — Asynchronous processing with Redis-backed job management
- **Real-Time Status** — Live updates on test execution progress
- **Artifact Management** — Persistent storage of test results, logs, and patches

### 📈 **Analytics & Insights**
- **Run Analytics** — Success rates, mode distribution, and trend analysis
- **Repository Statistics** — Track test performance across multiple repos
- **Performance Metrics** — Execution times, failure patterns, and improvement tracking
- **Visual Dashboards** — Interactive charts and graphs for data-driven insights
- **Export Capabilities** — Download run data as JSON or ZIP archives

### 🎨 **Modern UI/UX**
- **Single-Page Architecture** — Smooth state-driven transitions with React 19.2
- **Dark/Light Mode** — Beautiful theme system with system preference support
- **Mobile-First Design** — Fully responsive with optimized touch targets (44px+)
- **Real-Time Updates** — Live polling and WebSocket-ready architecture
- **Accessibility** — WCAG-compliant with keyboard navigation and screen reader support

### 🛡️ **Security & Safety**
- **Sandboxed Execution** — Tests run in isolated environments with command allowlists
- **Secure Token Storage** — GitHub tokens stored server-side only, never exposed to frontend
- **Input Validation** — Comprehensive sanitization and size limits
- **Rate Limiting** — API protection against abuse
- **CORS Protection** — Secure cross-origin resource sharing

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | React 19.2 with App Router for optimal performance |
| **TypeScript** | Type-safe development with strict mode |
| **Tailwind CSS** | Utility-first styling with custom design system |
| **shadcn/ui** | Accessible, customizable component library |
| **Lucide Icons** | Modern, consistent iconography |
| **Recharts** | Beautiful, responsive data visualizations |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance async Python API framework |
| **AutoGen** | Multi-agent orchestration for test generation |
| **OpenAI GPT-4.1-mini** | Intelligent code analysis and test generation |
| **Pydantic v2** | Data validation and serialization |
| **asyncio** | Non-blocking I/O for optimal performance |

### **Data & Infrastructure** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase Postgres** | Primary database with RPC functions for security |
| **Upstash Redis** | Job queue, caching, and real-time state management |
| **GitHub API** | Repository access and OAuth integration |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting with edge optimization |
| **Railway** | Backend API with auto-scaling |
| **Supabase** | Managed PostgreSQL with automatic backups |
| **Upstash** | Serverless Redis with global distribution |

---

## 📖 User Guide

### Getting Started

1. **Connect Repository** — Sign in with GitHub OAuth and authorize repository access
2. **Select Repository** — Choose from your connected repositories
3. **Choose Testing Mode** — Select unit, e2e, or both
4. **Customize Prompt** — Add specific instructions or use templates
5. **Run Analysis** — Watch AI agents analyze, generate, and execute tests
6. **Review Results** — Explore logs, failures, patches, and analytics

### Understanding Test Results

| Section | What It Shows |
|---------|---------------|
| **Test Plan** | AI-proposed strategy with files to test and rationale |
| **Generated Tests** | Complete test files created by the AI |
| **Execution Logs** | stdout/stderr from test runs |
| **Failure Analysis** | Detailed breakdown of test failures with root causes |
| **Patches** | Suggested code fixes as review-ready diffs |
| **Analytics** | Success rates, trends, and performance metrics |

### Testing Modes

- **Unit Tests** — Fast, isolated tests for individual functions/components
- **E2E Tests** — End-to-end tests for complete user workflows
- **Both** — Comprehensive coverage with both test types

### Pro Tips

- **Use Templates** — Save and reuse successful test configurations
- **Compare Runs** — Track improvements by comparing different test runs
- **Export Data** — Download run artifacts for offline analysis
- **Check Analytics** — Monitor trends to identify patterns
- **Iterate** — Use AI feedback to refine your code and tests

---

## 📊 Performance & Metrics

| Metric | Value |
|--------|-------|
| **Test Generation Time** | ~30-60 seconds (depending on codebase size) |
| **Frontend Bundle Size** | Optimized with code splitting |
| **API Response Time** | <200ms for most endpoints |
| **Real-Time Updates** | 3-second polling interval |
| **Mobile Performance** | 90+ Lighthouse score |
| **Accessibility** | WCAG 2.1 AA compliant |

---

## 🛡️ Security & Best Practices

- ✅ **Secure Token Storage** — GitHub tokens never exposed to frontend
- ✅ **Sandboxed Execution** — Tests run in isolated environments
- ✅ **Command Allowlisting** — Only safe, approved commands execute
- ✅ **Input Validation** — Comprehensive sanitization and size limits
- ✅ **Rate Limiting** — API protection against abuse
- ✅ **CORS Protection** — Secure cross-origin resource sharing
- ✅ **RPC Functions** — Database access through secure stored procedures
- ✅ **Environment Variables** — All secrets managed via env vars
- ✅ **Error Handling** — Graceful degradation with user-friendly messages

---

## 🧪 Testing & Quality Assurance

### Automated Testing
- **Unit Tests** — Comprehensive test coverage for core functionality
- **Integration Tests** — End-to-end API and database testing
- **Smoke Tests** — Quick verification of critical paths

### Code Quality
- **TypeScript** — Strict type checking for frontend
- **Pydantic** — Runtime validation for backend
- **ESLint** — Code linting and style enforcement
- **Pre-commit Hooks** — Automated quality checks

### Monitoring
- **Health Checks** — Automated service health monitoring
- **Error Logging** — Comprehensive error tracking and alerting
- **Performance Metrics** — Real-time performance monitoring
- **Analytics** — User behavior and system performance insights

---

## 🚀 Deployment

### Production Setup

**Frontend (Vercel):**
- Automatic deployments from main branch
- Environment variables configured in Vercel dashboard
- Edge optimization enabled
- Custom domain support

**Backend (Railway):**
- Automatic deployments from main branch
- Environment variables configured in Railway dashboard
- Auto-scaling based on traffic
- Health check endpoints for monitoring

**Database (Supabase):**
- Managed PostgreSQL with automatic backups
- RPC functions for secure data access
- Connection pooling for optimal performance

**Cache (Upstash):**
- Serverless Redis with global distribution
- Automatic scaling
- REST API for easy integration

---

## 📈 Roadmap & Enhancements

### Current Features (MVP)
- ✅ GitHub OAuth integration
- ✅ Multi-agent test generation
- ✅ Safe test execution
- ✅ Failure analysis and patches
- ✅ Real-time analytics
- ✅ Run comparison
- ✅ Template management
- ✅ Export capabilities

### Future Enhancements
- 🔄 GitLab integration
- 🔄 Automated PR creation with test results
- 🔄 Custom test framework support
- 🔄 Team collaboration features
- 🔄 Advanced code analysis
- 🔄 Integration with CI/CD pipelines

---

## 👨‍💻 Creator

**Derril Filemon**  
*AI Engineer & Fullstack Developer*

📍 Goteborg, SWEDEN  
📧 [LinkedIn](https://www.linkedin.com/in/derril-filemon-a31715319) • [GitHub](https://github.com/derril-tech)

This project showcases expertise in:

- 🤖 **AI/ML Engineering** — Multi-agent systems, OpenAI integration, prompt engineering
- ⚛️ **Modern Frontend** — Next.js 16, React 19.2, TypeScript, responsive design
- 🐍 **Backend Architecture** — FastAPI, async programming, microservices
- 🔄 **CI/CD & DevOps** — Automated testing, deployment pipelines, monitoring
- 📊 **Data Engineering** — Database design, caching strategies, analytics
- 🎨 **UI/UX Design** — User-centered design, accessibility, performance optimization
- 🛡️ **Security** — Secure authentication, input validation, safe execution
- ☁️ **Cloud Architecture** — Multi-platform deployment, scalability, reliability

---

## 🙏 Acknowledgments

- **[AutoGen](https://github.com/microsoft/autogen)** — Multi-agent framework inspiration
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini API
- **[GitHub](https://github.com/)** — OAuth and repository APIs
- **[Supabase](https://supabase.com/)** — Database and authentication
- **[Upstash](https://upstash.com/)** — Serverless Redis
- **[Railway](https://railway.app/)** — Backend hosting
- **[Vercel](https://vercel.com/)** — Frontend hosting
- **[shadcn/ui](https://ui.shadcn.com/)** — Beautiful component library

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">


Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
