# 🌐 Canific AI - Complete Tech Stack

![Website](https://img.shields.io/website?url=https://canific.dev)

**Canific AI** is a next-generation artificial intelligence platform designed to empower developers, researchers, and creatives with powerful tools for content creation, machine learning, and real-time data processing.

---

## 🚀 Features

### 🔍 Advanced Machine Learning
- **Semantic Kernel 1.38.0** for AI orchestration and plugin management
- **Ollama** support for local AI models (deepseek-r1:14b, llama3.1:8b)
- **Azure OpenAI** integration capabilities
- **Custom AI plugins** for specialized functionality

### ⚡ Real-Time Processing
- **RabbitMQ** message queuing with EasyNetQ for reliable communication
- **Background workers** for transcript processing and summarization
- **Real-time media processing** with FFMpegCore
- **High-volume data stream processing** with ultra-low latency

### Creative AI Tools
- **Google Drive & Docs API** integration for document management
- **Advanced media processing** with FFMpegCore
- **PDF generation** with jsPDF
- **HTML to canvas** conversion with html2canvas
- **Markdown processing** with react-markdown

### 🔒 Security & Authentication
- **JWT Bearer** authentication system
- **ASP.NET Identity** with role-based access control
- **Google OAuth** integration
- **Secure API endpoints** with proper authorization
- **CORS** configuration for production security

---

## 🧰 Tech Stack

### Frontend (CanificAIUI)
| Technology        | Version | Usage                                    |
|-------------------|---------|------------------------------------------|
| **Next.js**       | 14.2.24 | React framework with App Router          |
| **React**         | 18      | UI library                              |
| **TypeScript**    | 5.8.2   | Static typing and type safety           |
| **Tailwind CSS**  | 3.4.17  | Utility-first CSS framework             |
| **Radix UI**      | Latest  | Unstyled, accessible UI components      |
| **Framer Motion** | Latest  | Animations and transitions              |
| **React Hook Form**| 7.54.1  | Form handling and validation            |
| **Zod**           | 3.24.1  | Schema validation                       |
| **Axios**         | 1.9.0   | HTTP client for API calls               |
| **Lucide React**  | 0.454.0 | Icon library                            |
| **Sonner**        | 1.7.1   | Toast notifications                     |
| **Recharts**      | 2.15.0  | Data visualization charts                |
| **Embla Carousel**| 8.5.1   | Carousel component                      |
| **React Dropzone**| 14.3.8  | File upload handling                    |
| **Next Themes**   | Latest  | Dark/light theme switching              |

### Backend (CanAIBackend)
| Technology                    | Version | Usage                                    |
|-------------------------------|---------|------------------------------------------|
| **.NET**                     | 9.0     | Core framework and runtime               |
| **Entity Framework Core**    | 7.0.0   | Database ORM and migrations              |
| **SQL Server**               | -       | Primary database                         |
| **ASP.NET Identity**         | 7.0.0   | Authentication and authorization         |
| **JWT Bearer**               | 7.0.0   | Token-based authentication              |
| **Semantic Kernel**          | 1.38.0  | AI orchestration and plugin system       |
| **Ollama**                   | 1.15.0  | Local AI model support                   |
| **EasyNetQ**                 | 7.0.4   | Message queuing system                   |
| **FFMpegCore**               | 5.2.0   | Media processing                         |
| **Google APIs**              | 1.69.0  | Drive and Docs integration               |
| **RabbitMQ**                 | -       | Message broker for async processing      |
| **Serilog**                  | 9.0.0   | Structured logging                       |
| **Lemon Squezzy**               | 42.0.0  | Payment processing                       |
| **Newtonsoft.Json**          | 13.0.3  | JSON serialization                       |
| **Swashbuckle**              | 6.5.0   | API documentation (Swagger)              |

### Development & Build Tools
| Technology        | Usage                                    |
|-------------------|------------------------------------------|
| **PostCSS**       | CSS processing                           |
| **Autoprefixer**  | CSS vendor prefixing                     |
| **ESLint**        | Code linting                             |
| **TypeScript**    | Type checking                            |
| **Tailwind CSS**  | CSS framework with animations            |
| **Webpack**       | Module bundling (Next.js built-in)      |

### Infrastructure & Deployment
| Technology        | Usage                                    |
|-------------------|------------------------------------------|
| **IIS**           | Windows web server hosting               |
| **Node.js**       | Runtime for Next.js                      |
| **iisnode**       | IIS Node.js integration                  |
| **URL Rewrite**   | IIS URL rewriting module                 |
| **Windows Server**| Production hosting environment           |

### Third-Party Services
| Service           | Usage                                    |
|-------------------|------------------------------------------|
| **Google Gemini** | AI text generation and analysis          |
| **Google Drive**  | File storage and management              |
| **Google Docs**   | Document editing and collaboration       |
| **LemonSqueezy**  | Subscription and payment processing      |
| **SMTP**          | Email services                           |
| **Cloudflare**    | DNS, CDN, and security (production)     |

### Database & Storage
| Technology        | Usage                                    |
|-------------------|------------------------------------------|
| **SQL Server**    | Primary relational database              |
| **Entity Framework**| Database ORM and migrations             |

---

## Architecture

### Frontend Architecture
- **Next.js 14** with App Router for modern React development
- **Component-based** architecture with reusable UI components
- **Type-safe** development with TypeScript
- **Responsive design** with Tailwind CSS
- **State management** with React hooks and context

### Backend Architecture
- **Clean Architecture** with separation of concerns
- **Repository pattern** with Entity Framework Core
- **Service layer** for business logic
- **Background workers** for async processing
- **Plugin system** with Semantic Kernel
- **Message queuing** with RabbitMQ and EasyNetQ

### Data Flow
1. **Frontend** → **Next.js API Routes** → **Backend Controllers**
2. **Background Workers** → **Message Queue** → **Processing Services**
3. **AI Services** → **Semantic Kernel** → **External AI APIs**
4. **Database** → **Entity Framework** → **Repository Pattern**

---

> Built with ❤️ by the Canific AI Team.  
> Visit [Canific.dev](https://www.canific.dev) to learn more.
