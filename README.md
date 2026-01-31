# Document Management System (DMS) dengan Approval
**Blueprint & Technical Documentation**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Production Ready](https://img.shields.io/badge/Status-Production%20Ready-green.svg)]()
[![Version: 1.0](https://img.shields.io/badge/Version-1.0-blue.svg)]()

---

## 🛠️ Tech Stack

### Backend
![Node.js](https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-4.x-000000?style=for-the-badge&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Alternative Options:**
- ![Laravel](https://img.shields.io/badge/Laravel-10.x-FF2D20?style=flat-square&logo=laravel&logoColor=white) PHP + Laravel
- ![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?style=flat-square&logo=dotnet&logoColor=white) ASP.NET Core

### Frontend
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Alternative Options:**
- ![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D?style=flat-square&logo=vue.js&logoColor=white) Vue 3 + Nuxt
- ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-7952B3?style=flat-square&logo=bootstrap&logoColor=white) Traditional MVC

### Database
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-7.x-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Alternative:**
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-4169E1?style=flat-square&logo=postgresql&logoColor=white)
- ![MariaDB](https://img.shields.io/badge/MariaDB-10.5+-003545?style=flat-square&logo=mariadb&logoColor=white)

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-Latest-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-1.24-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-S3-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Alternative Cloud:**
- ![Azure](https://img.shields.io/badge/Azure-Blob-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
- ![GCP](https://img.shields.io/badge/GCP-Storage-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

### Tools & Libraries
![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-Realtime-010101?style=for-the-badge&logo=socket.io&logoColor=white)

### Testing
![Jest](https://img.shields.io/badge/Jest-Testing-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-E2E-17202C?style=for-the-badge&logo=cypress&logoColor=white)

### Monitoring & Logging
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 📑 Table of Contents

1. [Executive Summary](#executive-summary)
2. [Tujuan Sistem](#tujuan-sistem)
3. [Ruang Lingkup](#ruang-lingkup)
4. [Role & Hak Akses](#role--hak-akses)
5. [Workflow Approval](#workflow-approval)
6. [Metadata Dokumen](#metadata-dokumen)
7. [Manajemen Versi](#manajemen-versi)
8. [Database Schema](#database-schema)
9. [API Endpoints](#api-endpoints)
10. [UI/UX Design](#uiux-design)
11. [Keamanan & Compliance](#keamanan--compliance)
12. [File Management](#file-management)
13. [Notifikasi](#notifikasi)
14. [Reporting & Analytics](#reporting--analytics)
15. [Integration](#integration)
16. [Deployment](#deployment)
17. [Testing Strategy](#testing-strategy)
18. [Roadmap](#roadmap)

---

## 🎯 Executive Summary

Document Management System (DMS) dengan Approval adalah sistem manajemen dokumen enterprise-grade yang dirancang untuk mengontrol, melacak, dan mengelola dokumen perusahaan dengan alur persetujuan (approval workflow) yang terstruktur dan audit-ready.

### Key Features
- ✅ Centralized document repository
- ✅ Multi-level approval workflow
- ✅ Version control otomatis
- ✅ Role-based access control (RBAC)
- ✅ Full audit trail
- ✅ ISO compliance ready
- ✅ Real-time notifications
- ✅ Advanced search & filtering
- ✅ Mobile responsive
- ✅ RESTful API

### Target Industry
- Manufacturing
- Digital Transformation Projects
- OEE (Overall Equipment Effectiveness) Implementation
- ISO Compliance Organizations
- Enterprise with strict document control needs

---

## 🎯 Tujuan Sistem

### Primary Goals
1. **Centralized Storage**: Menyimpan dokumen perusahaan secara terpusat dan terstruktur
2. **Version Control**: Mengontrol versi dokumen agar tidak terjadi duplikasi
3. **Approval Workflow**: Menyediakan alur persetujuan yang jelas dan terdokumentasi
4. **Audit Support**: Mendukung kebutuhan audit (ISO, internal audit, compliance)
5. **Security & Integrity**: Menjaga keamanan dan integritas dokumen

### Business Benefits
- Mengurangi waktu pencarian dokumen hingga 80%
- Eliminasi dokumen duplikat
- Meningkatkan compliance rate
- Transparansi proses approval
- Audit trail lengkap untuk compliance

---

## 📂 Ruang Lingkup

### 2.1 Jenis Dokumen

#### 1. Dokumen Administratif
- Standard Operating Procedure (SOP)
- Policy perusahaan
- Surat resmi
- Memo internal

#### 2. Dokumen Operasional
- Work Instruction (WI)
- Manual mesin
- Form inspeksi
- Laporan OEE & downtime
- Checklist maintenance

#### 3. Dokumen Proyek & IT
- Dokumentasi sistem
- Diagram arsitektur
- Konfigurasi IoT / AVEVA Edge
- API documentation
- User manual

#### 4. Dokumen HR & Legal
- Job description
- Training material
- Sertifikat & audit
- Employment contract
- NDA & legal agreements

#### 5. Dokumen Quality
- Quality manual
- Inspection reports
- Non-conformance reports (NCR)
- Corrective action reports (CAR)

### 2.2 Document Classification

| Level | Description | Access |
|-------|-------------|--------|
| **Public** | Informasi umum | Semua user |
| **Internal** | Internal company | Authenticated users |
| **Confidential** | Data sensitif | Specific roles |
| **Secret** | Highly sensitive | Executive only |

---

## 👥 Role & Hak Akses

### 3.1 Role Definition

#### Admin
**Deskripsi**: Pengelola sistem dan super user

**Hak Akses**:
- ✅ Full access ke semua dokumen
- ✅ Manage users & roles
- ✅ View audit logs
- ✅ Publish & archive documents
- ✅ System configuration
- ✅ Backup & restore

**Use Case**: IT Department, System Administrator

---

#### Document Owner
**Deskripsi**: Pembuat dan pemilik dokumen

**Hak Akses**:
- ✅ Create new document
- ✅ Edit document (status Draft)
- ✅ Submit for review
- ✅ View approval status
- ✅ Revise rejected document
- ❌ Approve own document
- ❌ Delete approved document

**Use Case**: Engineer, Manager, Supervisor

---

#### Reviewer
**Deskripsi**: Pemeriksa isi dan validasi teknis

**Hak Akses**:
- ✅ Review assigned documents
- ✅ Approve atau Reject
- ✅ Add review comments
- ✅ Request clarification
- ❌ Edit document content
- ❌ Publish document

**Use Case**: Senior Engineer, Quality Assurance

---

#### Approver
**Deskripsi**: Pemberi persetujuan final

**Hak Akses**:
- ✅ Final approval
- ✅ Reject with reason
- ✅ Request revision
- ✅ Set effective date
- ❌ Edit document content

**Use Case**: Department Manager, Director

---

#### Viewer
**Deskripsi**: Pengguna akhir (read-only)

**Hak Akses**:
- ✅ View published documents
- ✅ Download documents
- ✅ Search & filter
- ❌ Edit or upload
- ❌ View draft documents

**Use Case**: Operator, General Staff

---

### 3.2 Access Control Matrix

| Action | Admin | Owner | Reviewer | Approver | Viewer |
|--------|-------|-------|----------|----------|--------|
| Create Document | ✅ | ✅ | ❌ | ❌ | ❌ |
| Edit Draft | ✅ | ✅ | ❌ | ❌ | ❌ |
| Submit Review | ✅ | ✅ | ❌ | ❌ | ❌ |
| Review Document | ✅ | ❌ | ✅ | ❌ | ❌ |
| Approve Document | ✅ | ❌ | ❌ | ✅ | ❌ |
| Publish Document | ✅ | ❌ | ❌ | ❌ | ❌ |
| View Published | ✅ | ✅ | ✅ | ✅ | ✅ |
| View Draft | ✅ | ✅ (own) | ✅ (assigned) | ✅ (assigned) | ❌ |
| Delete Document | ✅ | ✅ (draft only) | ❌ | ❌ | ❌ |
| Manage Users | ✅ | ❌ | ❌ | ❌ | ❌ |
| View Audit Log | ✅ | ❌ | ❌ | ❌ | ❌ |
| Archive Document | ✅ | ❌ | ❌ | ❌ | ❌ |

---

## 🔄 Workflow Approval

### 4.1 Status Dokumen

```
1. Draft       → Dokumen baru dibuat, masih dalam proses editing
2. Review      → Dokumen sudah disubmit, menunggu review
3. Approved    → Semua reviewer/approver sudah menyetujui
4. Published   → Dokumen aktif dan dapat digunakan
5. Archived    → Dokumen lama yang sudah tidak aktif
6. Rejected    → Dokumen ditolak, butuh revisi
```

### 4.2 Workflow Diagram

```
Owner Upload → Draft → Submit → Review
                 ↑                ↓
                 |          Reviewer Approve
                 |                ↓
                 |          Approver Check
                 |                ↓
                 └─ Reject ← Approved → Published → Archived
```

### 4.3 Business Rules

#### BR-001: Self-Approval Prevention
- Owner **TIDAK BOLEH** meng-approve dokumennya sendiri
- System akan block jika user adalah owner dan approver

#### BR-002: Sequential Approval
- Approver hanya bisa approve setelah semua Reviewer approve
- Tidak bisa "skip" reviewer

#### BR-003: Rejection Handling
- Jika ada 1 reject → dokumen kembali ke **Draft**
- Catatan reject **WAJIB** diisi
- Owner mendapat notifikasi rejection

#### BR-004: Version Locking
- Dokumen dengan status **Approved** atau **Published** tidak bisa diedit
- Untuk perubahan → buat versi baru

#### BR-005: Automatic Archiving
- Dokumen yang melewati `expiry_date` otomatis → **Archived**
- Archived document → read-only

#### BR-006: Review Cycle
- Dokumen Published wajib di-review berkala (sesuai `review_cycle`)
- System kirim reminder 30 hari sebelum review date

#### BR-007: Delegation
- Approver bisa delegate approval ke user lain
- Delegation tercatat di audit log

---

## 📋 Metadata Dokumen

### 5.1 Required Metadata (Wajib)

```javascript
{
  "title": "SOP Preventive Maintenance Mesin CNC",
  "doc_code": "SOP-MTC-001",
  "version": "2.1",
  "department": "Maintenance",
  "owner_id": 15,
  "owner_name": "Budi Santoso",
  "status": "Published",
  "created_at": "2024-01-15",
  "effective_date": "2024-02-01",
  "expiry_date": "2025-02-01",
  "review_cycle": 365,
  "classification": "Internal",
  "document_type": "SOP"
}
```

### 5.2 Document Naming Convention

```
[DOC_TYPE]-[DEPT]-[NUMBER]-[VERSION]

Examples:
- SOP-HR-001-v1.0.pdf
- WI-PRD-025-v2.3.pdf
- FORM-QC-010-v1.0.xlsx
- POL-IT-005-v3.0.docx
```

---

## 📊 Manajemen Versi

### 6.1 Version Numbering

**Format**: `MAJOR.MINOR`

- **MAJOR**: Perubahan signifikan (1.0 → 2.0)
  - Perubahan prosedur utama
  - Penambahan/penghapusan section besar

- **MINOR**: Perubahan kecil (1.0 → 1.1)
  - Perbaikan typo
  - Update informasi

**Examples**:
```
1.0  → Initial version
1.1  → Minor update
2.0  → Major revision
```

### 6.2 Version Changelog

```markdown
## Version 2.0 (2024-03-01)
### Changed
- Update prosedur preventive maintenance

### Added
- Form inspeksi baru
- Diagram troubleshooting

### Fixed
- Typo pada langkah 5
```


---

## 🗄️ Database Schema

### 7.1 Complete SQL Schema (MySQL/MariaDB)

```sql
-- ============================================================================
-- DATABASE: dms_approval
-- VERSION: 1.0
-- ============================================================================

CREATE DATABASE IF NOT EXISTS dms_approval 
CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

USE dms_approval;

-- ============================================================================
-- TABLE: users
-- ============================================================================
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL,
    role ENUM('Admin','Owner','Reviewer','Approver','Viewer') NOT NULL,
    department VARCHAR(100),
    phone VARCHAR(20),
    is_active BOOLEAN DEFAULT TRUE,
    last_login TIMESTAMP NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    
    INDEX idx_email (email),
    INDEX idx_role (role),
    INDEX idx_department (department)
) ENGINE=InnoDB;

-- ============================================================================
-- TABLE: documents
-- ============================================================================
CREATE TABLE documents (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(200) NOT NULL,
    doc_code VARCHAR(50) NOT NULL UNIQUE,
    current_version VARCHAR(10) DEFAULT '1.0',
    status ENUM('Draft','Review','Approved','Published','Archived','Rejected') DEFAULT 'Draft',
    owner_id INT NOT NULL,
    department VARCHAR(100),
    effective_date DATE,
    expiry_date DATE,
    review_cycle INT DEFAULT 365 COMMENT 'Review cycle in days',
    last_reviewed DATE,
    classification ENUM('Public','Internal','Confidential','Secret') DEFAULT 'Internal',
    document_type VARCHAR(50) COMMENT 'SOP, WI, FORM, POLICY, etc',
    description TEXT,
    keywords VARCHAR(255),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    
    FOREIGN KEY (owner_id) REFERENCES users(id) ON DELETE RESTRICT,
    
    INDEX idx_doc_code (doc_code),
    INDEX idx_status (status),
    INDEX idx_department (department),
    INDEX idx_document_type (document_type),
    FULLTEXT INDEX ft_title_description (title, description, keywords)
) ENGINE=InnoDB;

-- ============================================================================
-- TABLE: document_versions
-- ============================================================================
CREATE TABLE document_versions (
    id INT AUTO_INCREMENT PRIMARY KEY,
    document_id INT NOT NULL,
    version VARCHAR(10) NOT NULL,
    file_path VARCHAR(255) NOT NULL,
    file_name VARCHAR(255) NOT NULL,
    file_size BIGINT NOT NULL COMMENT 'File size in bytes',
    mime_type VARCHAR(100),
    checksum VARCHAR(64) COMMENT 'SHA-256 hash',
    changelog TEXT,
    created_by INT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    
    FOREIGN KEY (document_id) REFERENCES documents(id) ON DELETE CASCADE,
    FOREIGN KEY (created_by) REFERENCES users(id),
    
    INDEX idx_document_id (document_id),
    UNIQUE KEY unique_doc_version (document_id, version)
) ENGINE=InnoDB;

-- ============================================================================
-- TABLE: document_approvals
-- ============================================================================
CREATE TABLE document_approvals (
    id INT AUTO_INCREMENT PRIMARY KEY,
    document_id INT NOT NULL,
    approver_id INT NOT NULL,
    approval_role ENUM('Reviewer','Approver') NOT NULL,
    sequence_order INT DEFAULT 1,
    status ENUM('Pending','Approved','Rejected') DEFAULT 'Pending',
    note TEXT,
    action_date TIMESTAMP NULL,
    is_delegated BOOLEAN DEFAULT FALSE,
    delegated_by INT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    
    FOREIGN KEY (document_id) REFERENCES documents(id) ON DELETE CASCADE,
    FOREIGN KEY (approver_id) REFERENCES users(id),
    
    INDEX idx_document_id (document_id),
    INDEX idx_status (status),
    UNIQUE KEY unique_approval (document_id, approver_id, approval_role, sequence_order)
) ENGINE=InnoDB;

-- ============================================================================
-- TABLE: audit_logs
-- ============================================================================
CREATE TABLE audit_logs (
    id BIGINT AUTO_INCREMENT PRIMARY KEY,
    user_id INT NOT NULL,
    action VARCHAR(100) NOT NULL,
    entity_type VARCHAR(50),
    entity_id INT,
    document_id INT,
    description TEXT,
    ip_address VARCHAR(45),
    user_agent VARCHAR(255),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    
    FOREIGN KEY (user_id) REFERENCES users(id),
    
    INDEX idx_user_id (user_id),
    INDEX idx_action (action),
    INDEX idx_created_at (created_at)
) ENGINE=InnoDB;

-- ============================================================================
-- TABLE: notification_queue
-- ============================================================================
CREATE TABLE notification_queue (
    id BIGINT AUTO_INCREMENT PRIMARY KEY,
    user_id INT NOT NULL,
    type VARCHAR(50) NOT NULL,
    subject VARCHAR(200) NOT NULL,
    message TEXT NOT NULL,
    document_id INT,
    is_read BOOLEAN DEFAULT FALSE,
    sent BOOLEAN DEFAULT FALSE,
    sent_at TIMESTAMP NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    
    FOREIGN KEY (user_id) REFERENCES users(id) ON DELETE CASCADE,
    
    INDEX idx_user_id (user_id),
    INDEX idx_is_read (is_read)
) ENGINE=InnoDB;

-- ============================================================================
-- DEFAULT DATA
-- ============================================================================

INSERT INTO users (name, email, password, role, department) VALUES
('System Admin', 'admin@company.com', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', 'Admin', 'IT');

```

---

## 🔌 API Endpoints

### 8.1 Authentication

#### POST /api/auth/login
```json
Request:
{
  "email": "user@company.com",
  "password": "password123"
}

Response:
{
  "success": true,
  "data": {
    "token": "eyJhbGciOiJIUzI1NiIs...",
    "user": {
      "id": 1,
      "name": "John Doe",
      "role": "Owner"
    }
  }
}
```

### 8.2 Documents

#### GET /api/documents
```
Query: ?status=Published&department=Engineering&page=1&limit=20
```

#### POST /api/documents
Create new document with file upload

#### GET /api/documents/:id
Get document details

#### PUT /api/documents/:id
Update document (only Draft status)

#### DELETE /api/documents/:id
Delete document (only Draft status)

### 8.3 Approval Workflow

#### POST /api/documents/:id/submit
Submit document for review

#### POST /api/documents/:id/approve
Approve document

#### POST /api/documents/:id/reject
Reject document with notes

#### POST /api/documents/:id/publish
Publish document (Admin only)

### 8.4 Search & Reports

#### GET /api/search
Full-text search

#### GET /api/reports/dashboard
Dashboard statistics

#### GET /api/reports/approval-stats
Approval performance report

---

## 🎨 UI/UX Design

### 9.1 Design System

#### Color Palette
```css
/* Status Colors */
--status-draft: #6b7280;      /* Gray */
--status-review: #f59e0b;     /* Yellow */
--status-approved: #3b82f6;   /* Blue */
--status-published: #10b981;  /* Green */
--status-archived: #ef4444;   /* Red */
```

#### Status Badge
```html
<span class="badge badge-published">Published</span>
<span class="badge badge-review">Review</span>
<span class="badge badge-draft">Draft</span>
```

### 9.2 Page Layouts

#### Dashboard
```
┌────────┬────────────────────────┐
│        │  HEADER                │
│ SIDE   ├────────────────────────┤
│ BAR    │  Dashboard             │
│        │                        │
│        │  ┌─────┐ ┌─────┐      │
│ ┌────┐ │  │ 150 │ │ 15  │      │
│ │Home│ │  │Docs │ │Pend │      │
│ └────┘ │  └─────┘ └─────┘      │
│        │                        │
│ ┌────┐ │  Recent Documents      │
│ │Docs│ │  ┌──────────────────┐ │
│ └────┘ │  │ SOP-001  [Pub] 🟢│ │
│        │  └──────────────────┘ │
└────────┴────────────────────────┘
```

#### Document List
```
Search: [___________] 🔍

Filters: Status [All ▼] Dept [All ▼]

┌───────────────────────────────┐
│ Code    Title      Status     │
├───────────────────────────────┤
│ SOP-001 Prev Maint 🟢 Pub    │
│ WI-025  Assembly   🟡 Rev    │
└───────────────────────────────┘
```

### 9.3 Responsive Design

- **Desktop** (> 1024px): Full sidebar, multi-column layout
- **Tablet** (768px - 1024px): Collapsible sidebar
- **Mobile** (< 768px): Hamburger menu, stacked layout

---

## 🔒 Keamanan & Compliance

### 10.1 Authentication & Authorization

- JWT token-based authentication
- Password policy: Min 8 chars, uppercase, lowercase, number
- Session timeout: 30 minutes
- Role-based access control (RBAC)

### 10.2 Data Encryption

- **At Rest**: AES-256 encryption
- **In Transit**: TLS 1.3
- **Passwords**: bcrypt hashing

### 10.3 Audit Trail

Logged Actions:
- User login/logout
- Document CRUD operations
- Approval/rejection
- File downloads
- Failed login attempts

### 10.4 Compliance

#### ISO 9001:2015
✅ Version control
✅ Approval before use
✅ Document retention

#### ISO 27001
✅ Access control
✅ Cryptographic controls
✅ Asset management

---

## 📁 File Management

### 11.1 File Storage

**Options**:
1. **Local File System** (Development)
2. **Cloud Storage** (Production)
   - AWS S3
   - Azure Blob Storage
   - Google Cloud Storage

### 11.2 File Validation

```javascript
Allowed types: PDF, DOCX, XLSX, PPTX, PNG, JPG
Max size: 10MB
Virus scanning: ClamAV
Checksum: SHA-256
```

### 11.3 File Security

- Unique file names with timestamp
- Integrity verification via checksum
- Secure download with temporary tokens
- Access logging

---

## 🔔 Notifikasi

### 12.1 Notification Types

| Type | Trigger | Recipients |
|------|---------|------------|
| APPROVAL_REQUEST | Document submitted | Approvers |
| DOCUMENT_APPROVED | Approved | Owner |
| DOCUMENT_REJECTED | Rejected | Owner |
| DOCUMENT_EXPIRING | 30 days before | Owner |

### 12.2 Channels

- ✅ In-app notifications
- ✅ Email notifications
- ⬜ SMS (Optional)
- ⬜ Slack/Teams (Optional)

---

## 📊 Reporting & Analytics

### 13.1 Dashboard Metrics

```javascript
{
  total_documents: 150,
  pending_approvals: 15,
  expiring_soon: 8,
  avg_approval_time_hours: 48,
  compliance_rate: 95%
}
```

### 13.2 Standard Reports

1. **Document Inventory Report**
2. **Approval Performance Report**
3. **Document Expiration Report**
4. **User Activity Report**
5. **Department Compliance Report**

### 13.3 Export Formats

- PDF
- Excel (XLSX)
- CSV

---

## 🔌 Integration

### 14.1 API Integration

- RESTful API with JWT auth
- Webhook support
- API rate limiting

### 14.2 SSO Integration

- LDAP/Active Directory
- SAML 2.0
- OAuth 2.0

### 14.3 Third-Party Integration

- Google Drive sync
- Slack notifications
- Microsoft Teams
- Email systems (SMTP)

---

## 🚀 Deployment

### 15.1 System Requirements

**Minimum**:
- CPU: 2 cores
- RAM: 4 GB
- Storage: 50 GB SSD
- OS: Ubuntu 20.04 LTS

**Recommended (Production)**:
- CPU: 4-8 cores
- RAM: 16 GB
- Storage: 200 GB SSD
- Database: Dedicated server
- File Storage: Cloud (S3/Azure)

### 15.2 Docker Deployment

```bash
# Clone repository
git clone https://github.com/your-org/dms-approval.git
cd dms-approval

# Create .env file
cp .env.example .env

# Start with docker-compose
docker-compose up -d

# Check logs
docker-compose logs -f app
```

### 15.3 Environment Variables

```bash
# Application
NODE_ENV=production
APP_URL=https://dms.company.com
PORT=3000

# Database
DB_HOST=localhost
DB_PORT=3306
DB_NAME=dms_approval
DB_USER=dms_user
DB_PASSWORD=your_password

# Security
JWT_SECRET=your_jwt_secret
ENCRYPTION_KEY=your_encryption_key

# File Storage
FILE_STORAGE=s3
AWS_S3_BUCKET=dms-documents

# Email
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your_email
SMTP_PASSWORD=your_password
```

### 15.4 Backup & Recovery

```bash
# Database backup (daily at 2 AM)
0 2 * * * /opt/dms/backup/backup-db.sh

# File backup (daily at 3 AM)
0 3 * * * /opt/dms/backup/backup-files.sh
```

---

## 🧪 Testing Strategy

### 16.1 Test Types

```
E2E Tests (10%)
Integration Tests (30%)
Unit Tests (60%)
```

### 16.2 Testing Tools

- **Unit Tests**: Jest / Mocha
- **Integration Tests**: Supertest
- **E2E Tests**: Cypress / Selenium
- **Performance**: k6 / JMeter

---

## 🗺️ Roadmap

### Phase 1: MVP (Month 1-2) ✅
- [x] Core document management
- [x] Basic approval workflow
- [x] User management & RBAC
- [x] Version control
- [x] Basic notifications

### Phase 2: Enhancement (Month 3-4) 🚧
- [ ] Advanced search
- [ ] Bulk operations
- [ ] Mobile responsive
- [ ] Advanced workflows
- [ ] Report export

### Phase 3: Integration (Month 5-6) 📋
- [ ] API documentation
- [ ] SSO integration
- [ ] Third-party integrations
- [ ] Mobile app

### Phase 4: Advanced (Month 7-9) 🔮
- [ ] AI-powered features
- [ ] OCR support
- [ ] Digital signatures
- [ ] Multi-language

### Phase 5: Enterprise (Month 10-12) 🏢
- [ ] Multi-tenancy
- [ ] Advanced compliance
- [ ] Blockchain audit log
- [ ] High availability

---

## 📚 Additional Resources

### Documentation
- [Installation Guide](docs/INSTALLATION.md)
- [User Manual](docs/USER_MANUAL.md)
- [API Reference](docs/API.md)
- [Admin Guide](docs/ADMIN_GUIDE.md)

### Support
- **Email**: support@yourcompany.com
- **Documentation**: https://docs.dms.yourcompany.com

---

## 📋 Tech Stack Recommendations

### Backend Options

**Option 1: Node.js + Express**
```javascript
- Express.js (API Framework)
- Sequelize / Prisma (ORM)
- JWT (Authentication)
- Multer (File Upload)
- Bull (Queue)
- Winston (Logging)
```

**Option 2: PHP + Laravel**
```php
- Laravel 10
- Laravel Passport (API Auth)
- Laravel Queue
- Laravel Storage
- Intervention Image
```

**Option 3: ASP.NET Core**
```csharp
- ASP.NET Core 8
- Entity Framework Core
- Identity Server
- SignalR (Real-time)
```

### Frontend Options

**Option 1: React + Vite**
```
- React 18
- Vite
- TailwindCSS
- React Query
- Zustand (State)
```

**Option 2: Vue.js**
```
- Vue 3
- Nuxt 3
- Pinia
- TailwindCSS
```

**Option 3: Traditional MVC**
```
- Server-side rendering
- Bootstrap 5
- jQuery (minimal)
```

### Database

**Primary**: MySQL 8.0 / MariaDB 10.5
**Alternative**: PostgreSQL 14+

### Cache & Queue

- Redis 6.0+
- RabbitMQ (alternative)

### File Storage

- **Development**: Local filesystem
- **Production**: AWS S3 / Azure Blob / MinIO

---

## 🎯 Success Metrics

### KPIs to Track

1. **Document Management**
   - Total documents managed
   - Documents published/month
   - Average time to publish

2. **Approval Efficiency**
   - Average approval time
   - Approval success rate
   - Rejection rate & reasons

3. **User Adoption**
   - Active users/month
   - Documents accessed/user
   - Search usage

4. **Compliance**
   - Documents within expiry
   - Overdue reviews
   - Audit trail completeness

5. **System Performance**
   - API response time (< 200ms)
   - Uptime (99.9%)
   - Storage utilization

---

## ⚠️ Important Notes

### Before Production

- [ ] Change all default passwords
- [ ] Configure SSL/TLS certificates
- [ ] Set up backup automation
- [ ] Configure monitoring
- [ ] Set up firewall rules
- [ ] Enable audit logging
- [ ] Test disaster recovery
- [ ] Perform security audit
- [ ] Load testing
- [ ] User acceptance testing

### Security Checklist

- [ ] Strong password policy enforced
- [ ] 2FA enabled for admin
- [ ] Regular security updates
- [ ] Database encrypted
- [ ] Files encrypted at rest
- [ ] HTTPS only
- [ ] Rate limiting enabled
- [ ] Input validation
- [ ] SQL injection prevention
- [ ] XSS protection

---

## 🙏 Acknowledgments

- MySQL for reliable database
- Redis for caching excellence
- Node.js community
- TailwindCSS for beautiful UI
- All open-source contributors

---

## 📄 License

This project blueprint is provided as-is for implementation purposes.

---

## 👥 Contact & Support

**Questions?** Feel free to:
- Open an issue on GitHub
- Email: dms-support@yourcompany.com
- Documentation: Read the docs

---

**Made with ❤️ for better document management**

© 2024 Your Company Name. All rights reserved.

---

## 🚀 Quick Start

```bash
# 1. Clone repository
git clone https://github.com/your-org/dms-approval.git
cd dms-approval

# 2. Install dependencies
npm install

# 3. Setup environment
cp .env.example .env
# Edit .env with your configuration

# 4. Setup database
mysql -u root -p < database/schema.sql

# 5. Run migrations
npm run migrate

# 6. Start development server
npm run dev

# 7. Access application
# http://localhost:3000
```

Default credentials:
- Email: `admin@company.com`
- Password: `admin123` (CHANGE THIS!)

---

## 📖 Quick Reference

### Document Status Flow
```
Draft → Review → Approved → Published → Archived
  ↑       ↓
  └── Rejected
```

### User Roles
```
Admin > Approver > Reviewer > Owner > Viewer
```

### API Base URL
```
https://api.dms.yourcompany.com/v1
```

---

**End of Documentation**

Happy coding! 🎉
