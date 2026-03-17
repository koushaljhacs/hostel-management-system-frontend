
# 🏥 Hospital Management System - Frontend

<p align="center">
  <a href="https://koushaljhacs.github.io/hostel-management-system-frontend/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Preview-Visit%20Website-blue?style=for-the-badge&logo=github" alt="Live Preview">
  </a>
</p>

> For a GUI-based view of the project, please visit the live website. Thank you!

**Version:** 8.0.0 | **Total Files:** 699 | **Deadline:** 2026-04-12


> Complete frontend blueprint for Hospital Management System with 16 user roles. Every file is synchronized with backend API and database schema. No deviations allowed.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Team Structure](#team-structure)
- [File Structure](#file-structure)
- [Quick Start](#quick-start)
- [Development Standards](#development-standards)
- [Git Workflow](#git-workflow)
- [VS Code Setup](#vs-code-setup)
- [File Headers](#file-headers)
- [Naming Conventions](#naming-conventions)
- [Module Breakdown](#module-breakdown)
- [Deadline](#deadline)
- [Backend API](#backend-api)
- [FAQ](#faq)

---

## 🏥 Project Overview

The Hospital Management System frontend consists of **699 files** across 16 user roles. This project is split equally between two developers: Sundram (350 files) and Suyash (349 files). Every file name, folder structure, and naming convention must be followed exactly to ensure seamless API integration.

**Key Statistics:**
- HTML Pages: 584
- CSS Files: 22
- JavaScript Files: 24
- Images: 55
- Fonts: 7
- Config Files: 7

---

## 👥 Team Structure

| Developer | Files | Primary Modules |
|-----------|-------|-----------------|
| **Sundram** | 350 | auth, public, patient, doctor, nurse, receptionist + shared |
| **Suyash** | 349 | pharmacist, lab, radiologist, billing, admin + shared |

---

## 📁 File Structure
```
├── frontend/                                             ➕ NEED TO CREATE (HTML/CSS/JS)
│   ├── assets/
│   │   ├── css/
│   │   │   ├── main.css                                  ➕ NEED TO CREATE
│   │   │   ├── auth.css                                  ➕ NEED TO CREATE
│   │   │   ├── dashboard.css                             ➕ NEED TO CREATE
│   │   │   ├── patient.css                               ➕ NEED TO CREATE
│   │   │   ├── doctor.css                                ➕ NEED TO CREATE
│   │   │   ├── nurse.css                                 ➕ NEED TO CREATE
│   │   │   ├── pharmacist.css                            ➕ NEED TO CREATE
│   │   │   ├── lab.css                                   ➕ NEED TO CREATE
│   │   │   ├── billing.css                               ➕ NEED TO CREATE
│   │   │   ├── admin.css                                 ➕ NEED TO CREATE
│   │   │   ├── components.css                            ➕ NEED TO CREATE
│   │   │   ├── forms.css                                 ➕ NEED TO CREATE
│   │   │   ├── tables.css                                ➕ NEED TO CREATE
│   │   │   ├── cards.css                                 ➕ NEED TO CREATE
│   │   │   ├── modals.css                                ➕ NEED TO CREATE
│   │   │   ├── alerts.css                                ➕ NEED TO CREATE
│   │   │   ├── print.css                                 ➕ NEED TO CREATE
│   │   │   ├── responsive.css                            ➕ NEED TO CREATE
│   │   │   └── themes/
│   │   │       ├── light.css                             ➕ NEED TO CREATE
│   │   │       └── dark.css                              ➕ NEED TO CREATE
│   │   ├── js/
│   │   │   ├── main.js                                   ➕ NEED TO CREATE
│   │   │   ├── api.js                                    ➕ NEED TO CREATE
│   │   │   ├── auth.js                                   ➕ NEED TO CREATE
│   │   │   ├── utils.js                                  ➕ NEED TO CREATE
│   │   │   ├── validation.js                             ➕ NEED TO CREATE
│   │   │   ├── formatters.js                             ➕ NEED TO CREATE
│   │   │   ├── charts.js                                 ➕ NEED TO CREATE
│   │   │   ├── tables.js                                 ➕ NEED TO CREATE
│   │   │   ├── modals.js                                 ➕ NEED TO CREATE
│   │   │   ├── alerts.js                                 ➕ NEED TO CREATE
│   │   │   ├── dropdowns.js                              ➕ NEED TO CREATE
│   │   │   ├── tabs.js                                   ➕ NEED TO CREATE
│   │   │   ├── accordion.js                              ➕ NEED TO CREATE
│   │   │   ├── carousel.js                               ➕ NEED TO CREATE
│   │   │   ├── websocket.js                              ➕ NEED TO CREATE
│   │   │   ├── errorHandler.js                           ➕ NEED TO CREATE
│   │   │   ├── logger.js                                 ➕ NEED TO CREATE
│   │   │   ├── config.js                                 ➕ NEED TO CREATE
│   │   │   └── vendors/
│   │   │       ├── bootstrap.js                          ➕ NEED TO CREATE
│   │   │       ├── jquery.js                             ➕ NEED TO CREATE
│   │   │       ├── moment.js                             ➕ NEED TO CREATE
│   │   │       ├── chart.js                              ➕ NEED TO CREATE
│   │   │       └── datatable.js                          ➕ NEED TO CREATE
│   │   ├── images/
│   │   │   ├── logo.png                                  ➕ NEED TO CREATE
│   │   │   ├── logo-white.png                            ➕ NEED TO CREATE
│   │   │   ├── favicon.ico                               ➕ NEED TO CREATE
│   │   │   ├── favicon-16x16.png                         ➕ NEED TO CREATE
│   │   │   ├── favicon-32x32.png                         ➕ NEED TO CREATE
│   │   │   ├── apple-touch-icon.png                      ➕ NEED TO CREATE
│   │   │   ├── android-chrome-192x192.png                ➕ NEED TO CREATE
│   │   │   ├── android-chrome-512x512.png                ➕ NEED TO CREATE
│   │   │   ├── og-image.png                              ➕ NEED TO CREATE
│   │   │   ├── placeholders/
│   │   │   │   ├── doctor.jpg                            ➕ NEED TO CREATE
│   │   │   │   ├── patient.jpg                           ➕ NEED TO CREATE
│   │   │   │   ├── nurse.jpg                             ➕ NEED TO CREATE
│   │   │   │   ├── staff.jpg                             ➕ NEED TO CREATE
│   │   │   │   ├── hospital.jpg                          ➕ NEED TO CREATE
│   │   │   │   ├── lab.jpg                               ➕ NEED TO CREATE
│   │   │   │   └── pharmacy.jpg                          ➕ NEED TO CREATE
│   │   │   ├── backgrounds/
│   │   │   │   ├── login-bg.jpg                          ➕ NEED TO CREATE
│   │   │   │   ├── dashboard-bg.jpg                      ➕ NEED TO CREATE
│   │   │   │   └── profile-bg.jpg                        ➕ NEED TO CREATE
│   │   │   └── icons/
│   │   │       ├── dashboard.svg                         ➕ NEED TO CREATE
│   │   │       ├── patients.svg                          ➕ NEED TO CREATE
│   │   │       ├── appointments.svg                      ➕ NEED TO CREATE
│   │   │       ├── prescriptions.svg                     ➕ NEED TO CREATE
│   │   │       ├── lab.svg                               ➕ NEED TO CREATE
│   │   │       ├── pharmacy.svg                          ➕ NEED TO CREATE
│   │   │       ├── billing.svg                           ➕ NEED TO CREATE
│   │   │       ├── reports.svg                           ➕ NEED TO CREATE
│   │   │       ├── settings.svg                          ➕ NEED to CREATE
│   │   │       ├── logout.svg                            ➕ NEED TO CREATE
│   │   │       ├── profile.svg                           ➕ NEED TO CREATE
│   │   │       ├── notification.svg                      ➕ NEED TO CREATE
│   │   │       ├── search.svg                            ➕ NEED TO CREATE
│   │   │       ├── filter.svg                            ➕ NEED TO CREATE
│   │   │       ├── sort.svg                              ➕ NEED TO CREATE
│   │   │       ├── add.svg                               ➕ NEED TO CREATE
│   │   │       ├── edit.svg                              ➕ NEED TO CREATE
│   │   │       ├── delete.svg                            ➕ NEED TO CREATE
│   │   │       ├── view.svg                              ➕ NEED TO CREATE
│   │   │       ├── download.svg                          ➕ NEED TO CREATE
│   │   │       ├── upload.svg                            ➕ NEED TO CREATE
│   │   │       ├── print.svg                             ➕ NEED TO CREATE
│   │   │       ├── email.svg                             ➕ NEED TO CREATE
│   │   │       ├── sms.svg                               ➕ NEED TO CREATE
│   │   │       ├── whatsapp.svg                          ➕ NEED TO CREATE
│   │   │       ├── calendar.svg                          ➕ NEED TO CREATE
│   │   │       ├── clock.svg                             ➕ NEED TO CREATE
│   │   │       ├── location.svg                          ➕ NEED TO CREATE
│   │   │       ├── phone.svg                             ➕ NEED TO CREATE
│   │   │       └── emergency.svg                         ➕ NEED TO CREATE
│   │   └── fonts/                                        ➕ NEED TO CREATE
│   │       ├── inter-regular.woff2                       ➕ NEED TO CREATE
│   │       ├── inter-medium.woff2                        ➕ NEED TO CREATE
│   │       ├── inter-bold.woff2                          ➕ NEED TO CREATE
│   │       ├── roboto-regular.woff2                      ➕ NEED TO CREATE
│   │       ├── roboto-medium.woff2                       ➕ NEED TO CREATE
│   │       ├── roboto-bold.woff2                         ➕ NEED TO CREATE
│   │       └── README.md                                 ➕ NEED TO CREATE
│   │
│   ├── pages/                                            ➕ NEED TO CREATE
│   │   ├── auth/
│   │   │   ├── login.html                                ➕ NEED TO CREATE
│   │   │   ├── register.html                             ➕ NEED TO CREATE
│   │   │   ├── forgot-password.html                      ➕ NEED TO CREATE
│   │   │   ├── reset-password.html                       ➕ NEED TO CREATE
│   │   │   ├── verify-email.html                         ➕ NEED TO CREATE
│   │   │   ├── verify-phone.html                         ➕ NEED TO CREATE
│   │   │   ├── mfa-setup.html                            ➕ NEED TO CREATE
│   │   │   ├── mfa-verify.html                           ➕ NEED TO CREATE
│   │   │   ├── select-role.html                          ➕ NEED TO CREATE
│   │   │   └── index.html                                ➕ NEED TO CREATE
│   │   ├── public/
│   │   │   ├── index.html                                ➕ NEED TO CREATE
│   │   │   ├── home.html                                 ➕ NEED TO CREATE
│   │   │   ├── about.html                                ➕ NEED TO CREATE
│   │   │   ├── contact.html                              ➕ NEED TO CREATE
│   │   │   ├── doctors.html                              ➕ NEED TO CREATE
│   │   │   ├── doctor-detail.html                        ➕ NEED TO CREATE
│   │   │   ├── departments.html                          ➕ NEED TO CREATE
│   │   │   ├── department-detail.html                    ➕ NEED TO CREATE
│   │   │   ├── services.html                             ➕ NEED TO CREATE
│   │   │   ├── service-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── facilities.html                           ➕ NEED TO CREATE
│   │   │   ├── insurance.html                            ➕ NEED TO CREATE
│   │   │   ├── insurance-detail.html                     ➕ NEED TO CREATE
│   │   │   ├── appointment-booking.html                  ➕ NEED TO CREATE
│   │   │   ├── check-availability.html                   ➕ NEED TO CREATE
│   │   │   ├── faq.html                                  ➕ NEED TO CREATE
│   │   │   ├── announcements.html                        ➕ NEED TO CREATE
│   │   │   ├── careers.html                              ➕ NEED TO CREATE
│   │   │   ├── gallery.html                              ➕ NEED TO CREATE
│   │   │   ├── testimonials.html                         ➕ NEED TO CREATE
│   │   │   ├── blog.html                                 ➕ NEED TO CREATE
│   │   │   ├── blog-detail.html                          ➕ NEED TO CREATE
│   │   │   ├── privacy-policy.html                       ➕ NEED TO CREATE
│   │   │   ├── terms.html                                ➕ NEED TO CREATE
│   │   │   └── sitemap.html                              ➕ NEED TO CREATE
│   │   ├── patient/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── profile.html                              ➕ NEED TO CREATE
│   │   │   ├── profile-edit.html                         ➕ NEED TO CREATE
│   │   │   ├── emergency-contacts.html                   ➕ NEED TO CREATE
│   │   │   ├── emergency-contact-add.html                ➕ NEED TO CREATE
│   │   │   ├── emergency-contact-edit.html               ➕ NEED TO CREATE
│   │   │   ├── medical-records.html                      ➕ NEED TO CREATE
│   │   │   ├── medical-summary.html                      ➕ NEED TO CREATE
│   │   │   ├── timeline.html                             ➕ NEED TO CREATE
│   │   │   ├── prescriptions.html                        ➕ NEED TO CREATE
│   │   │   ├── prescription-detail.html                  ➕ NEED TO CREATE
│   │   │   ├── prescription-download.html                ➕ NEED TO CREATE
│   │   │   ├── lab-results.html                          ➕ NEED TO CREATE
│   │   │   ├── lab-result-detail.html                    ➕ NEED TO CREATE
│   │   │   ├── lab-result-download.html                  ➕ NEED TO CREATE
│   │   │   ├── radiology-images.html                     ➕ NEED TO CREATE
│   │   │   ├── radiology-image-detail.html               ➕ NEED TO CREATE
│   │   │   ├── radiology-image-download.html             ➕ NEED TO CREATE
│   │   │   ├── vitals.html                               ➕ NEED TO CREATE
│   │   │   ├── vitals-chart.html                         ➕ NEED TO CREATE
│   │   │   ├── diagnosis.html                            ➕ NEED TO CREATE
│   │   │   ├── visits.html                               ➕ NEED TO CREATE
│   │   │   ├── visit-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── appointments.html                         ➕ NEED TO CREATE
│   │   │   ├── appointment-detail.html                   ➕ NEED TO CREATE
│   │   │   ├── appointment-book.html                     ➕ NEED TO CREATE
│   │   │   ├── appointment-reschedule.html               ➕ NEED TO CREATE
│   │   │   ├── appointment-cancel.html                   ➕ NEED TO CREATE
│   │   │   ├── billing.html                              ➕ NEED TO CREATE
│   │   │   ├── invoices.html                             ➕ NEED TO CREATE
│   │   │   ├── invoice-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── invoice-download.html                     ➕ NEED TO CREATE
│   │   │   ├── payments.html                             ➕ NEED TO CREATE
│   │   │   ├── payment-methods.html                      ➕ NEED TO CREATE
│   │   │   ├── payment-method-add.html                   ➕ NEED TO CREATE
│   │   │   ├── insurance.html                            ➕ NEED TO CREATE
│   │   │   ├── insurance-claims.html                     ➕ NEED TO CREATE
│   │   │   ├── claim-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── coverage-check.html                       ➕ NEED TO CREATE
│   │   │   ├── consents.html                             ➕ NEED TO CREATE
│   │   │   ├── consent-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── consent-sign.html                         ➕ NEED TO CREATE
│   │   │   ├── data-export.html                          ➕ NEED TO CREATE
│   │   │   ├── deletion-request.html                     ➕ NEED TO CREATE
│   │   │   ├── notifications.html                        ➕ NEED TO CREATE
│   │   │   └── notification-settings.html                ➕ NEED TO CREATE
│   │   ├── doctor/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── patients.html                             ➕ NEED TO CREATE
│   │   │   ├── patient-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── patient-history.html                      ➕ NEED TO CREATE
│   │   │   ├── patient-vitals.html                       ➕ NEED TO CREATE
│   │   │   ├── patient-lab-results.html                  ➕ NEED TO CREATE
│   │   │   ├── patient-radiology.html                    ➕ NEED TO CREATE
│   │   │   ├── patient-prescriptions.html                ➕ NEED TO CREATE
│   │   │   ├── appointments.html                         ➕ NEED TO CREATE
│   │   │   ├── appointment-detail.html                   ➕ NEED TO CREATE
│   │   │   ├── appointment-calendar.html                 ➕ NEED TO CREATE
│   │   │   ├── appointment-stats.html                    ➕ NEED TO CREATE
│   │   │   ├── prescriptions.html                        ➕ NEED TO CREATE
│   │   │   ├── prescription-create.html                  ➕ NEED TO CREATE
│   │   │   ├── prescription-edit.html                    ➕ NEED TO CREATE
│   │   │   ├── prescription-detail.html                  ➕ NEED TO CREATE
│   │   │   ├── prescription-templates.html               ➕ NEED TO CREATE
│   │   │   ├── prescription-template-create.html         ➕ NEED TO CREATE
│   │   │   ├── lab-orders.html                           ➕ NEED TO CREATE
│   │   │   ├── lab-order-create.html                     ➕ NEED TO CREATE
│   │   │   ├── lab-order-detail.html                     ➕ NEED TO CREATE
│   │   │   ├── lab-tests.html                            ➕ NEED TO CREATE
│   │   │   ├── radiology-orders.html                     ➕ NEED TO CREATE
│   │   │   ├── radiology-order-create.html               ➕ NEED TO CREATE
│   │   │   ├── radiology-order-detail.html               ➕ NEED TO CREATE
│   │   │   ├── diagnosis.html                            ➕ NEED TO CREATE
│   │   │   ├── diagnosis-create.html                     ➕ NEED TO CREATE
│   │   │   ├── diagnosis-edit.html                       ➕ NEED TO CREATE
│   │   │   ├── clinical-notes.html                       ➕ NEED TO CREATE
│   │   │   ├── clinical-note-create.html                 ➕ NEED TO CREATE
│   │   │   ├── clinical-note-edit.html                   ➕ NEED TO CREATE
│   │   │   ├── schedule.html                             ➕ NEED TO CREATE
│   │   │   ├── schedule-edit.html                        ➕ NEED TO CREATE
│   │   │   ├── availability.html                         ➕ NEED TO CREATE
│   │   │   ├── availability-edit.html                    ➕ NEED TO CREATE
│   │   │   ├── leaves.html                               ➕ NEED TO CREATE
│   │   │   ├── leave-apply.html                          ➕ NEED TO CREATE
│   │   │   ├── performance.html                          ➕ NEED TO CREATE
│   │   │   ├── performance-stats.html                    ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── nurse/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── patients.html                             ➕ NEED TO CREATE
│   │   │   ├── patient-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── patient-vitals.html                       ➕ NEED TO CREATE
│   │   │   ├── patient-medications.html                  ➕ NEED TO CREATE
│   │   │   ├── patient-tasks.html                        ➕ NEED TO CREATE
│   │   │   ├── vitals.html                               ➕ NEED TO CREATE
│   │   │   ├── vital-record.html                         ➕ NEED TO CREATE
│   │   │   ├── vital-history.html                        ➕ NEED TO CREATE
│   │   │   ├── vital-charts.html                         ➕ NEED TO CREATE
│   │   │   ├── tasks.html                                ➕ NEED TO CREATE
│   │   │   ├── task-detail.html                          ➕ NEED TO CREATE
│   │   │   ├── task-assign.html                          ➕ NEED TO CREATE
│   │   │   ├── medications.html                          ➕ NEED TO CREATE
│   │   │   ├── medication-schedule.html                  ➕ NEED TO CREATE
│   │   │   ├── medication-administer.html                ➕ NEED TO CREATE
│   │   │   ├── medication-history.html                   ➕ NEED TO CREATE
│   │   │   ├── beds.html                                 ➕ NEED TO CREATE
│   │   │   ├── bed-detail.html                           ➕ NEED TO CREATE
│   │   │   ├── bed-allocate.html                         ➕ NEED TO CREATE
│   │   │   ├── bed-occupancy.html                        ➕ NEED TO CREATE
│   │   │   ├── bed-cleaning-schedule.html                ➕ NEED TO CREATE
│   │   │   ├── handover.html                             ➕ NEED TO CREATE
│   │   │   ├── handover-create.html                      ➕ NEED TO CREATE
│   │   │   ├── handover-view.html                        ➕ NEED TO CREATE
│   │   │   ├── shift.html                                ➕ NEED TO CREATE
│   │   │   ├── shift-current.html                        ➕ NEED TO CREATE
│   │   │   ├── shift-schedule.html                       ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── receptionist/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── registration.html                         ➕ NEED TO CREATE
│   │   │   ├── patient-search.html                       ➕ NEED TO CREATE
│   │   │   ├── patient-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── patient-edit.html                         ➕ NEED TO CREATE
│   │   │   ├── patient-deactivate.html                   ➕ NEED TO CREATE
│   │   │   ├── emergency-contact-add.html                ➕ NEED TO CREATE
│   │   │   ├── appointments.html                         ➕ NEED TO CREATE
│   │   │   ├── appointment-create.html                   ➕ NEED TO CREATE
│   │   │   ├── appointment-detail.html                   ➕ NEED TO CREATE
│   │   │   ├── appointment-edit.html                     ➕ NEED TO CREATE
│   │   │   ├── appointment-cancel.html                   ➕ NEED TO CREATE
│   │   │   ├── appointment-check-in.html                 ➕ NEED TO CREATE
│   │   │   ├── appointment-check-out.html                ➕ NEED TO CREATE
│   │   │   ├── appointment-calendar.html                 ➕ NEED TO CREATE
│   │   │   ├── available-slots.html                      ➕ NEED TO CREATE
│   │   │   ├── walk-in.html                              ➕ NEED TO CREATE
│   │   │   ├── walk-in-register.html                     ➕ NEED TO CREATE
│   │   │   ├── walk-in-queue.html                        ➕ NEED TO CREATE
│   │   │   ├── beds.html                                 ➕ NEED TO CREATE
│   │   │   ├── bed-availability.html                     ➕ NEED TO CREATE
│   │   │   ├── bed-allocate.html                         ➕ NEED TO CREATE
│   │   │   ├── bed-vacate.html                           ➕ NEED TO CREATE
│   │   │   ├── bed-occupancy.html                        ➕ NEED TO CREATE
│   │   │   ├── opd.html                                  ➕ NEED TO CREATE
│   │   │   ├── opd-token.html                            ➕ NEED TO CREATE
│   │   │   ├── opd-queue.html                            ➕ NEED TO CREATE
│   │   │   ├── opd-register.html                         ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── pharmacist/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── inventory.html                            ➕ NEED TO CREATE
│   │   │   ├── inventory-detail.html                     ➕ NEED TO CREATE
│   │   │   ├── inventory-add.html                        ➕ NEED TO CREATE
│   │   │   ├── inventory-edit.html                       ➕ NEED TO CREATE
│   │   │   ├── inventory-search.html                     ➕ NEED TO CREATE
│   │   │   ├── low-stock.html                            ➕ NEED TO CREATE
│   │   │   ├── out-of-stock.html                         ➕ NEED TO CREATE
│   │   │   ├── expiring.html                             ➕ NEED TO CREATE
│   │   │   ├── expired.html                              ➕ NEED TO CREATE
│   │   │   ├── stock-in.html                             ➕ NEED TO CREATE
│   │   │   ├── stock-out.html                            ➕ NEED TO CREATE
│   │   │   ├── stock-history.html                        ➕ NEED TO CREATE
│   │   │   ├── batches.html                              ➕ NEED TO CREATE
│   │   │   ├── batch-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── batch-add.html                            ➕ NEED TO CREATE
│   │   │   ├── prescriptions.html                        ➕ NEED TO CREATE
│   │   │   ├── prescription-pending.html                 ➕ NEED TO CREATE
│   │   │   ├── prescription-dispensed.html               ➕ NEED TO CREATE
│   │   │   ├── prescription-detail.html                  ➕ NEED TO CREATE
│   │   │   ├── dispensing.html                           ➕ NEED TO CREATE
│   │   │   ├── dispense.html                             ➕ NEED TO CREATE
│   │   │   ├── dispense-history.html                     ➕ NEED TO CREATE
│   │   │   ├── dispense-today.html                       ➕ NEED TO CREATE
│   │   │   ├── suppliers.html                            ➕ NEED TO CREATE
│   │   │   ├── supplier-detail.html                      ➕ NEED TO CREATE
│   │   │   ├── supplier-add.html                         ➕ NEED TO CREATE
│   │   │   ├── supplier-edit.html                        ➕ NEED TO CREATE
│   │   │   ├── supplier-products.html                    ➕ NEED TO CREATE
│   │   │   ├── purchase-orders.html                      ➕ NEED TO CREATE
│   │   │   ├── purchase-order-detail.html                ➕ NEED TO CREATE
│   │   │   ├── purchase-order-create.html                ➕ NEED TO CREATE
│   │   │   ├── purchase-order-edit.html                  ➕ NEED TO CREATE
│   │   │   ├── purchase-order-receive.html               ➕ NEED TO CREATE
│   │   │   ├── returns.html                              ➕ NEED TO CREATE
│   │   │   ├── return-create.html                        ➕ NEED TO CREATE
│   │   │   ├── return-history.html                       ➕ NEED TO CREATE
│   │   │   ├── expiry-dispose.html                       ➕ NEED TO CREATE
│   │   │   ├── expiry-report.html                        ➕ NEED TO CREATE
│   │   │   ├── reports.html                              ➕ NEED TO CREATE
│   │   │   ├── inventory-report.html                     ➕ NEED TO CREATE
│   │   │   ├── consumption-report.html                   ➕ NEED TO CREATE
│   │   │   ├── dispensing-report.html                    ➕ NEED TO CREATE
│   │   │   ├── expiry-report.html                        ➕ NEED TO CREATE
│   │   │   ├── purchase-report.html                      ➕ NEED TO CREATE
│   │   │   ├── supplier-performance.html                 ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── lab-technician/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── orders.html                               ➕ NEED TO CREATE
│   │   │   ├── order-pending.html                        ➕ NEED TO CREATE
│   │   │   ├── order-in-progress.html                    ➕ NEED TO CREATE
│   │   │   ├── order-completed.html                      ➕ NEED TO CREATE
│   │   │   ├── order-urgent.html                         ➕ NEED TO CREATE
│   │   │   ├── order-stat.html                           ➕ NEED TO CREATE
│   │   │   ├── order-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── order-collect.html                        ➕ NEED TO CREATE
│   │   │   ├── order-receive.html                        ➕ NEED TO CREATE
│   │   │   ├── order-start.html                          ➕ NEED TO CREATE
│   │   │   ├── order-complete.html                       ➕ NEED TO CREATE
│   │   │   ├── results.html                              ➕ NEED TO CREATE
│   │   │   ├── result-pending.html                       ➕ NEED TO CREATE
│   │   │   ├── result-completed.html                     ➕ NEED TO CREATE
│   │   │   ├── result-abnormal.html                      ➕ NEED TO CREATE
│   │   │   ├── result-critical.html                      ➕ NEED TO CREATE
│   │   │   ├── result-detail.html                        ➕ NEED TO CREATE
│   │   │   ├── result-entry.html                         ➕ NEED TO CREATE
│   │   │   ├── result-edit.html                          ➕ NEED TO CREATE
│   │   │   ├── result-verify.html                        ➕ NEED TO CREATE
│   │   │   ├── result-approve.html                       ➕ NEED TO CREATE
│   │   │   ├── result-report.html                        ➕ NEED TO CREATE
│   │   │   ├── specimens.html                            ➕ NEED TO CREATE
│   │   │   ├── specimen-collected.html                   ➕ NEED TO CREATE
│   │   │   ├── specimen-received.html                    ➕ NEED TO CREATE
│   │   │   ├── specimen-processed.html                   ➕ NEED TO CREATE
│   │   │   ├── specimen-rejected.html                    ➕ NEED TO CREATE
│   │   │   ├── specimen-detail.html                      ➕ NEED TO CREATE
│   │   │   ├── specimen-register.html                    ➕ NEED TO CREATE
│   │   │   ├── specimen-condition.html                   ➕ NEED TO CREATE
│   │   │   ├── specimen-reject.html                      ➕ NEED TO CREATE
│   │   │   ├── specimen-dispose.html                     ➕ NEED TO CREATE
│   │   │   ├── specimen-tracking.html                    ➕ NEED TO CREATE
│   │   │   ├── equipment.html                            ➕ NEED TO CREATE
│   │   │   ├── equipment-operational.html                ➕ NEED TO CREATE
│   │   │   ├── equipment-maintenance.html                ➕ NEED TO CREATE
│   │   │   ├── equipment-calibration.html                ➕ NEED TO CREATE
│   │   │   ├── equipment-detail.html                     ➕ NEED TO CREATE
│   │   │   ├── equipment-calibration-log.html            ➕ NEED TO CREATE
│   │   │   ├── equipment-usage.html                      ➕ NEED TO CREATE
│   │   │   ├── qc.html                                   ➕ NEED TO CREATE
│   │   │   ├── qc-records.html                           ➕ NEED TO CREATE
│   │   │   ├── qc-add.html                               ➕ NEED TO CREATE
│   │   │   ├── qc-detail.html                            ➕ NEED TO CREATE
│   │   │   ├── qc-stats.html                             ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── radiologist/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── orders.html                               ➕ NEED TO CREATE
│   │   │   ├── order-pending.html                        ➕ NEED TO CREATE
│   │   │   ├── order-completed.html                      ➕ NEED TO CREATE
│   │   │   ├── order-urgent.html                         ➕ NEED TO CREATE
│   │   │   ├── order-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── order-start.html                          ➕ NEED TO CREATE
│   │   │   ├── order-complete.html                       ➕ NEED TO CREATE
│   │   │   ├── images.html                               ➕ NEED TO CREATE
│   │   │   ├── image-pending.html                        ➕ NEED TO CREATE
│   │   │   ├── image-reported.html                       ➕ NEED TO CREATE
│   │   │   ├── image-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── image-upload.html                         ➕ NEED TO CREATE
│   │   │   ├── image-viewer.html                         ➕ NEED TO CREATE
│   │   │   ├── image-download.html                       ➕ NEED TO CREATE
│   │   │   ├── image-rotate.html                         ➕ NEED TO CREATE
│   │   │   ├── image-annotate.html                       ➕ NEED TO CREATE
│   │   │   ├── reports.html                              ➕ NEED TO CREATE
│   │   │   ├── report-pending.html                       ➕ NEED TO CREATE
│   │   │   ├── report-completed.html                     ➕ NEED TO CREATE
│   │   │   ├── report-detail.html                        ➕ NEED TO CREATE
│   │   │   ├── report-create.html                        ➕ NEED TO CREATE
│   │   │   ├── report-edit.html                          ➕ NEED TO CREATE
│   │   │   ├── report-submit.html                        ➕ NEED TO CREATE
│   │   │   ├── report-verify.html                        ➕ NEED TO CREATE
│   │   │   ├── report-download.html                      ➕ NEED TO CREATE
│   │   │   ├── equipment.html                            ➕ NEED TO CREATE
│   │   │   ├── equipment-detail.html                     ➕ NEED TO CREATE
│   │   │   ├── equipment-status.html                     ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── billing/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── invoices.html                             ➕ NEED TO CREATE
│   │   │   ├── invoice-draft.html                        ➕ NEED TO CREATE
│   │   │   ├── invoice-pending.html                      ➕ NEED TO CREATE
│   │   │   ├── invoice-paid.html                         ➕ NEED TO CREATE
│   │   │   ├── invoice-overdue.html                      ➕ NEED TO CREATE
│   │   │   ├── invoice-cancelled.html                    ➕ NEED TO CREATE
│   │   │   ├── invoice-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── invoice-create.html                       ➕ NEED TO CREATE
│   │   │   ├── invoice-edit.html                         ➕ NEED TO CREATE
│   │   │   ├── invoice-submit.html                       ➕ NEED TO CREATE
│   │   │   ├── invoice-approve.html                      ➕ NEED TO CREATE
│   │   │   ├── invoice-cancel.html                       ➕ NEED TO CREATE
│   │   │   ├── invoice-pdf.html                          ➕ NEED TO CREATE
│   │   │   ├── invoice-breakdown.html                    ➕ NEED TO CREATE
│   │   │   ├── payments.html                             ➕ NEED TO CREATE
│   │   │   ├── payment-online.html                       ➕ NEED TO CREATE
│   │   │   ├── payment-cash.html                         ➕ NEED TO CREATE
│   │   │   ├── payment-card.html                         ➕ NEED TO CREATE
│   │   │   ├── payment-upi.html                          ➕ NEED TO CREATE
│   │   │   ├── payment-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── payment-record.html                       ➕ NEED TO CREATE
│   │   │   ├── payment-verify.html                       ➕ NEED TO CREATE
│   │   │   ├── payment-summary.html                      ➕ NEED TO CREATE
│   │   │   ├── refunds.html                              ➕ NEED TO CREATE
│   │   │   ├── refund-pending.html                       ➕ NEED TO CREATE
│   │   │   ├── refund-completed.html                     ➕ NEED TO CREATE
│   │   │   ├── refund-detail.html                        ➕ NEED TO CREATE
│   │   │   ├── refund-process.html                       ➕ NEED TO CREATE
│   │   │   ├── refund-approve.html                       ➕ NEED TO CREATE
│   │   │   ├── insurance-claims.html                     ➕ NEED TO CREATE
│   │   │   ├── claim-draft.html                          ➕ NEED TO CREATE
│   │   │   ├── claim-submitted.html                      ➕ NEED TO CREATE
│   │   │   ├── claim-approved.html                       ➕ NEED TO CREATE
│   │   │   ├── claim-rejected.html                       ➕ NEED TO CREATE
│   │   │   ├── claim-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── claim-create.html                         ➕ NEED TO CREATE
│   │   │   ├── claim-submit.html                         ➕ NEED TO CREATE
│   │   │   ├── claim-track.html                          ➕ NEED TO CREATE
│   │   │   ├── tax-rates.html                            ➕ NEED TO CREATE
│   │   │   ├── tax-rate-add.html                         ➕ NEED TO CREATE
│   │   │   ├── tax-rate-edit.html                        ➕ NEED TO CREATE
│   │   │   ├── discounts.html                            ➕ NEED TO CREATE
│   │   │   ├── discount-add.html                         ➕ NEED TO CREATE
│   │   │   ├── discount-edit.html                        ➕ NEED TO CREATE
│   │   │   ├── reports.html                              ➕ NEED TO CREATE
│   │   │   ├── daily-report.html                         ➕ NEED TO CREATE
│   │   │   ├── weekly-report.html                        ➕ NEED TO CREATE
│   │   │   ├── monthly-report.html                       ➕ NEED TO CREATE
│   │   │   ├── yearly-report.html                        ➕ NEED TO CREATE
│   │   │   ├── revenue-report.html                       ➕ NEED TO CREATE
│   │   │   ├── outstanding-report.html                   ➕ NEED TO CREATE
│   │   │   ├── insurance-report.html                     ➕ NEED TO CREATE
│   │   │   ├── tax-report.html                           ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── admin/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── users.html                                ➕ NEED TO CREATE
│   │   │   ├── user-search.html                          ➕ NEED TO CREATE
│   │   │   ├── user-detail.html                          ➕ NEED TO CREATE
│   │   │   ├── user-create.html                          ➕ NEED TO CREATE
│   │   │   ├── user-edit.html                            ➕ NEED TO CREATE
│   │   │   ├── user-permissions.html                     ➕ NEED TO CREATE
│   │   │   ├── user-roles.html                           ➕ NEED TO CREATE
│   │   │   ├── user-audit.html                           ➕ NEED TO CREATE
│   │   │   ├── roles.html                                ➕ NEED TO CREATE
│   │   │   ├── role-detail.html                          ➕ NEED TO CREATE
│   │   │   ├── role-create.html                          ➕ NEED TO CREATE
│   │   │   ├── role-edit.html                            ➕ NEED TO CREATE
│   │   │   ├── role-permissions.html                     ➕ NEED TO CREATE
│   │   │   ├── permissions.html                          ➕ NEED TO CREATE
│   │   │   ├── permission-detail.html                    ➕ NEED TO CREATE
│   │   │   ├── permission-create.html                    ➕ NEED TO CREATE
│   │   │   ├── permission-edit.html                      ➕ NEED TO CREATE
│   │   │   ├── departments.html                          ➕ NEED TO CREATE
│   │   │   ├── department-detail.html                    ➕ NEED TO CREATE
│   │   │   ├── department-create.html                    ➕ NEED TO CREATE
│   │   │   ├── department-edit.html                      ➕ NEED TO CREATE
│   │   │   ├── department-employees.html                 ➕ NEED TO CREATE
│   │   │   ├── shifts.html                               ➕ NEED TO CREATE
│   │   │   ├── shift-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── shift-create.html                         ➕ NEED TO CREATE
│   │   │   ├── shift-edit.html                           ➕ NEED TO CREATE
│   │   │   ├── shift-assignments.html                    ➕ NEED TO CREATE
│   │   │   ├── system-health.html                        ➕ NEED TO CREATE
│   │   │   ├── system-metrics.html                       ➕ NEED TO CREATE
│   │   │   ├── system-logs.html                          ➕ NEED TO CREATE
│   │   │   ├── system-performance.html                   ➕ NEED TO CREATE
│   │   │   ├── system-backup.html                        ➕ NEED TO CREATE
│   │   │   ├── system-backups.html                       ➕ NEED TO CREATE
│   │   │   ├── system-maintenance.html                   ➕ NEED TO CREATE
│   │   │   ├── system-maintenance-schedule.html          ➕ NEED TO CREATE
│   │   │   ├── system-maintenance-logs.html              ➕ NEED TO CREATE
│   │   │   ├── security-audit-logs.html                  ➕ NEED TO CREATE
│   │   │   ├── security-phi-access.html                  ➕ NEED TO CREATE
│   │   │   ├── security-break-glass.html                 ➕ NEED TO CREATE
│   │   │   ├── security-login-attempts.html              ➕ NEED TO CREATE
│   │   │   ├── security-sessions.html                    ➕ NEED TO CREATE
│   │   │   ├── security-encryption.html                  ➕ NEED TO CREATE
│   │   │   ├── billing-tax-rates.html                    ➕ NEED TO CREATE
│   │   │   ├── billing-discounts.html                    ➕ NEED TO CREATE
│   │   │   ├── billing-insurance-providers.html          ➕ NEED TO CREATE
│   │   │   ├── billing-payment-methods.html              ➕ NEED TO CREATE
│   │   │   ├── billing-pricing.html                      ➕ NEED TO CREATE
│   │   │   ├── config.html                               ➕ NEED TO CREATE
│   │   │   ├── config-email.html                         ➕ NEED TO CREATE
│   │   │   ├── config-sms.html                           ➕ NEED TO CREATE
│   │   │   ├── config-payment.html                       ➕ NEED TO CREATE
│   │   │   ├── config-backup.html                        ➕ NEED TO CREATE
│   │   │   ├── audit-all.html                            ➕ NEED TO CREATE
│   │   │   ├── audit-users.html                          ➕ NEED TO CREATE
│   │   │   ├── audit-phi.html                            ➕ NEED TO CREATE
│   │   │   ├── audit-security.html                       ➕ NEED TO CREATE
│   │   │   ├── audit-system.html                         ➕ NEED TO CREATE
│   │   │   ├── audit-export.html                         ➕ NEED TO CREATE
│   │   │   ├── reports.html                              ➕ NEED TO CREATE
│   │   │   ├── user-report.html                          ➕ NEED TO CREATE
│   │   │   ├── role-report.html                          ➕ NEED TO CREATE
│   │   │   ├── permission-report.html                    ➕ NEED TO CREATE
│   │   │   ├── audit-report.html                         ➕ NEED TO CREATE
│   │   │   ├── security-report.html                      ➕ NEED TO CREATE
│   │   │   ├── billing-report.html                       ➕ NEED TO CREATE
│   │   │   ├── financial-report.html                     ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── ground-staff/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── tasks.html                                ➕ NEED TO CREATE
│   │   │   ├── task-pending.html                         ➕ NEED TO CREATE
│   │   │   ├── task-completed.html                       ➕ NEED TO CREATE
│   │   │   ├── task-today.html                           ➕ NEED TO CREATE
│   │   │   ├── task-priority.html                        ➕ NEED TO CREATE
│   │   │   ├── task-detail.html                          ➕ NEED TO CREATE
│   │   │   ├── task-accept.html                          ➕ NEED TO CREATE
│   │   │   ├── task-reject.html                          ➕ NEED TO CREATE
│   │   │   ├── task-start.html                           ➕ NEED TO CREATE
│   │   │   ├── task-complete.html                        ➕ NEED TO CREATE
│   │   │   ├── task-postpone.html                        ➕ NEED TO CREATE
│   │   │   ├── transport.html                            ➕ NEED TO CREATE
│   │   │   ├── transport-pending.html                    ➕ NEED TO CREATE
│   │   │   ├── transport-completed.html                  ➕ NEED TO CREATE
│   │   │   ├── transport-detail.html                     ➕ NEED TO CREATE
│   │   │   ├── transport-accept.html                     ➕ NEED TO CREATE
│   │   │   ├── transport-start.html                      ➕ NEED TO CREATE
│   │   │   ├── transport-complete.html                   ➕ NEED TO CREATE
│   │   │   ├── transport-history.html                    ➕ NEED TO CREATE
│   │   │   ├── samples.html                              ➕ NEED TO CREATE
│   │   │   ├── sample-pending.html                       ➕ NEED TO CREATE
│   │   │   ├── sample-collected.html                     ➕ NEED TO CREATE
│   │   │   ├── sample-delivered.html                     ➕ NEED TO CREATE
│   │   │   ├── sample-detail.html                        ➕ NEED TO CREATE
│   │   │   ├── sample-collect.html                       ➕ NEED TO CREATE
│   │   │   ├── sample-deliver.html                       ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── security/
│   │   │   ├── dashboard.html                            ➕ NEED TO CREATE
│   │   │   ├── entries.html                              ➕ NEED TO CREATE
│   │   │   ├── entries-today.html                        ➕ NEED TO CREATE
│   │   │   ├── entry-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── entry-record.html                         ➕ NEED TO CREATE
│   │   │   ├── entry-exit.html                           ➕ NEED TO CREATE
│   │   │   ├── entries-active.html                       ➕ NEED TO CREATE
│   │   │   ├── exits.html                                ➕ NEED TO CREATE
│   │   │   ├── exits-today.html                          ➕ NEED TO CREATE
│   │   │   ├── exit-record.html                          ➕ NEED TO CREATE
│   │   │   ├── visitors.html                             ➕ NEED TO CREATE
│   │   │   ├── visitors-active.html                      ➕ NEED TO CREATE
│   │   │   ├── visitor-detail.html                       ➕ NEED TO CREATE
│   │   │   ├── visitor-register.html                     ➕ NEED TO CREATE
│   │   │   ├── visitor-check-out.html                    ➕ NEED TO CREATE
│   │   │   ├── visitor-history.html                      ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── employee/
│   │   │   ├── profile.html                              ➕ NEED TO CREATE
│   │   │   ├── profile-edit.html                         ➕ NEED TO CREATE
│   │   │   ├── profile-photo.html                        ➕ NEED TO CREATE
│   │   │   ├── shifts.html                               ➕ NEED TO CREATE
│   │   │   ├── shift-current.html                        ➕ NEED TO CREATE
│   │   │   ├── shift-upcoming.html                       ➕ NEED TO CREATE
│   │   │   ├── shift-history.html                        ➕ NEED TO CREATE
│   │   │   ├── shift-calendar.html                       ➕ NEED TO CREATE
│   │   │   ├── attendance.html                           ➕ NEED TO CREATE
│   │   │   ├── attendance-today.html                     ➕ NEED TO CREATE
│   │   │   ├── attendance-history.html                   ➕ NEED TO CREATE
│   │   │   ├── attendance-summary.html                   ➕ NEED TO CREATE
│   │   │   ├── attendance-monthly.html                   ➕ NEED TO CREATE
│   │   │   ├── leaves.html                               ➕ NEED TO CREATE
│   │   │   ├── leave-balance.html                        ➕ NEED TO CREATE
│   │   │   ├── leave-history.html                        ➕ NEED TO CREATE
│   │   │   ├── leave-detail.html                         ➕ NEED TO CREATE
│   │   │   ├── leave-apply.html                          ➕ NEED TO CREATE
│   │   │   ├── leave-cancel.html                         ➕ NEED TO CREATE
│   │   │   ├── documents.html                            ➕ NEED TO CREATE
│   │   │   ├── document-detail.html                      ➕ NEED TO CREATE
│   │   │   ├── document-upload.html                      ➕ NEED TO CREATE
│   │   │   ├── notifications.html                        ➕ NEED TO CREATE
│   │   │   ├── notification-settings.html                ➕ NEED TO CREATE
│   │   │   └── settings.html                             ➕ NEED TO CREATE
│   │   ├── reports/
│   │   │   ├── patient-reports.html                      ➕ NEED TO CREATE
│   │   │   ├── patient-daily.html                        ➕ NEED TO CREATE
│   │   │   ├── patient-monthly.html                      ➕ NEED TO CREATE
│   │   │   ├── patient-yearly.html                       ➕ NEED to CREATE
│   │   │   ├── patient-demographics.html                 ➕ NEED TO CREATE
│   │   │   ├── patient-visits.html                       ➕ NEED TO CREATE
│   │   │   ├── clinical-reports.html                     ➕ NEED TO CREATE
│   │   │   ├── diagnosis-report.html                     ➕ NEED TO CREATE
│   │   │   ├── prescription-report.html                  ➕ NEED TO CREATE
│   │   │   ├── lab-report.html                           ➕ NEED TO CREATE
│   │   │   ├── radiology-report.html                     ➕ NEED TO CREATE
│   │   │   ├── financial-reports.html                    ➕ NEED TO CREATE
│   │   │   ├── revenue-report.html                       ➕ NEED TO CREATE
│   │   │   ├── outstanding-report.html                   ➕ NEED TO CREATE
│   │   │   ├── insurance-report.html                     ➕ NEED TO CREATE
│   │   │   ├── tax-report.html                           ➕ NEED TO CREATE
│   │   │   ├── operational-reports.html                  ➕ NEED TO CREATE
│   │   │   ├── appointment-report.html                   ➕ NEED TO CREATE
│   │   │   ├── bed-occupancy-report.html                 ➕ NEED TO CREATE
│   │   │   ├── inventory-report.html                     ➕ NEED TO CREATE
│   │   │   ├── equipment-report.html                     ➕ NEED TO CREATE
│   │   │   ├── export.html                               ➕ NEED TO CREATE
│   │   │   ├── export-patients.html                      ➕ NEED TO CREATE
│   │   │   ├── export-appointments.html                  ➕ NEED TO CREATE
│   │   │   ├── export-invoices.html                      ➕ NEED TO CREATE
│   │   │   ├── export-inventory.html                     ➕ NEED TO CREATE
│   │   │   ├── export-audit-logs.html                    ➕ NEED TO CREATE
│   │   │   └── index.html                                ➕ NEED TO CREATE
│   │   └── error/
│   │       ├── 400.html                                  ➕ NEED TO CREATE
│   │       ├── 401.html                                  ➕ NEED TO CREATE
│   │       ├── 403.html                                  ➕ NEED TO CREATE
│   │       ├── 404.html                                  ➕ NEED TO CREATE
│   │       ├── 409.html                                  ➕ NEED TO CREATE
│   │       ├── 422.html                                  ➕ NEED TO CREATE
│   │       ├── 429.html                                  ➕ NEED TO CREATE
│   │       ├── 500.html                                  ➕ NEED TO CREATE
│   │       ├── 502.html                                  ➕ NEED TO CREATE
│   │       ├── 503.html                                  ➕ NEED TO CREATE
│   │       ├── 504.html                                  ➕ NEED TO CREATE
│   │       └── index.html                                ➕ NEED TO CREATE
│   │
│   ├── components/                                        ➕ NEED TO CREATE
│   │   ├── header.html                                   ➕ NEED TO CREATE
│   │   ├── footer.html                                   ➕ NEED TO CREATE
│   │   ├── sidebar.html                                  ➕ NEED TO CREATE
│   │   ├── navbar.html                                   ➕ NEED TO CREATE
│   │   ├── breadcrumb.html                               ➕ NEED TO CREATE
│   │   ├── modal.html                                    ➕ NEED TO CREATE
│   │   ├── alert.html                                    ➕ NEED TO CREATE
│   │   ├── toast.html                                    ➕ NEED TO CREATE
│   │   ├── loader.html                                   ➕ NEED TO CREATE
│   │   ├── spinner.html                                  ➕ NEED TO CREATE
│   │   ├── pagination.html                               ➕ NEED TO CREATE
│   │   ├── table.html                                    ➕ NEED TO CREATE
│   │   ├── card.html                                     ➕ NEED TO CREATE
│   │   ├── badge.html                                    ➕ NEED TO CREATE
│   │   ├── tabs.html                                     ➕ NEED TO CREATE
│   │   ├── accordion.html                                ➕ NEED TO CREATE
│   │   ├── dropdown.html                                 ➕ NEED TO CREATE
│   │   ├── tooltip.html                                  ➕ NEED TO CREATE
│   │   ├── popover.html                                  ➕ NEED TO CREATE
│   │   ├── progress.html                                 ➕ NEED TO CREATE
│   │   ├── stepper.html                                  ➕ NEED TO CREATE
│   │   ├── timeline.html                                 ➕ NEED TO CREATE
│   │   ├── patient-card.html                             ➕ NEED TO CREATE
│   │   ├── doctor-card.html                              ➕ NEED TO CREATE
│   │   ├── appointment-card.html                         ➕ NEED TO CREATE
│   │   ├── prescription-card.html                        ➕ NEED TO CREATE
│   │   ├── medicine-card.html                            ➕ NEED TO CREATE
│   │   ├── bed-card.html                                 ➕ NEED TO CREATE
│   │   ├── invoice-card.html                             ➕ NEED TO CREATE
│   │   ├── task-item.html                                ➕ NEED TO CREATE
│   │   ├── notification-item.html                        ➕ NEED TO CREATE
│   │   ├── comment.html                                  ➕ NEED TO CREATE
│   │   ├── rating.html                                   ➕ NEED TO CREATE
│   │   ├── search-bar.html                               ➕ NEED TO CREATE
│   │   ├── filter-bar.html                               ➕ NEED TO CREATE
│   │   ├── date-picker.html                              ➕ NEED TO CREATE
│   │   ├── time-picker.html                              ➕ NEED TO CREATE
│   │   ├── file-upload.html                              ➕ NEED TO CREATE
│   │   ├── image-upload.html                             ➕ NEED TO CREATE
│   │   ├── signature-pad.html                            ➕ NEED TO CREATE
│   │   └── index.html                                    ➕ NEED TO CREATE
│   │
│   ├── layouts/                                           ➕ NEED TO CREATE
│   │   ├── auth-layout.html                              ➕ NEED TO CREATE
│   │   ├── public-layout.html                            ➕ NEED TO CREATE
│   │   ├── patient-layout.html                           ➕ NEED TO CREATE
│   │   ├── doctor-layout.html                            ➕ NEED TO CREATE
│   │   ├── nurse-layout.html                             ➕ NEED TO CREATE
│   │   ├── receptionist-layout.html                      ➕ NEED TO CREATE
│   │   ├── pharmacist-layout.html                        ➕ NEED TO CREATE
│   │   ├── lab-layout.html                               ➕ NEED TO CREATE
│   │   ├── radiologist-layout.html                       ➕ NEED TO CREATE
│   │   ├── billing-layout.html                           ➕ NEED TO CREATE
│   │   ├── admin-layout.html                             ➕ NEED TO CREATE
│   │   ├── ground-staff-layout.html                      ➕ NEED TO CREATE
│   │   ├── security-layout.html                          ➕ NEED TO CREATE
│   │   ├── employee-layout.html                          ➕ NEED TO CREATE
│   │   └── error-layout.html                             ➕ NEED TO CREATE
│   │
│   ├── index.html                                         ➕ NEED TO CREATE
│   ├── 404.html                                           ➕ NEED TO CREATE
│   ├── 500.html                                           ➕ NEED TO CREATE
│   ├── manifest.json                                      ➕ NEED TO CREATE
│   ├── robots.txt                                         ➕ NEED TO CREATE
│   ├── sitemap.xml                                        ➕ NEED TO CREATE
│   ├── browserconfig.xml                                  ➕ NEED TO CREATE
│   ├── .htaccess                                          ➕ NEED TO CREATE
│   ├── web.config                                         ➕ NEED TO CREATE
│   └── README.md                                          ➕ NEED TO CREATE

```
---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/koushaljhacs/hostel-management-system-frontend.git

# Navigate to project directory
cd hostel-management-system-frontend

# Create your feature branch
git checkout -b feature/your-name-module

# Start coding!
```

---

### 🎨 Development Standards
#### HTML Standards
Use semantic HTML5 tags (header, nav, main, section, article, footer)

Include proper meta tags in every page

Follow W3C compliance

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Page description">
    <meta name="author" content="Developer Name">
    <title>Hospital Management - Page Title</title>
    <link rel="stylesheet" href="../../assets/css/main.css">
</head>
<body>
    <!-- Content -->
</body>
</html>
```

#### CSS Standards (BEM)
```css
/* Block */
.patient-card {
    background: white;
}

/* Element (double underscore) */
.patient-card__header {
    border-bottom: 1px solid #eee;
}

/* Modifier (double hyphen) */
.patient-card--featured {
    border: 2px solid gold;
}
```

#### JavaScript Standards (ES6+)
```javascript
'use strict';

// Constants (use const by default)
const API_BASE_URL = 'http://100.81.13.80/api/v1';

// Variables that change (use let)
let currentPage = 1;

// Async function
async function fetchPatientData(patientId) {
    try {
        const response = await fetch(`${API_BASE_URL}/patients/${patientId}`);
        const data = await response.json();
        return data;
    } catch (error) {
        console.error('Error fetching patient:', error);
    }
}
```
---

### 📝 Naming Conventions
| Type                 | Format                    | Example                     |
| -------------------- | ------------------------- | --------------------------- |
| HTML Files           | kebab-case                | `patient-dashboard.html`    |
| CSS Files            | kebab-case                | `patient-dashboard.css`     |
| JavaScript Files     | kebab-case                | `patient-dashboard.js`      |
| JavaScript Variables | camelCase                 | `let patientName = '';`     |
| JavaScript Constants | UPPER_SNAKE_CASE          | `const API_URL = '';`        |
| CSS Classes (BEM)    | block__element--modifier  | `patient-card__title--large`|
| Image Files          | kebab-case                | `doctor-placeholder.jpg`    |
| Folders              | kebab-case                | `lab-technician/`           |
| Data Attributes      | data-kebab-case           | `data-patient-id="123"`     |

---

### 📄 File Headers
Every file must include a header with the following format:

#### HTML Header
```html
<!-- =========================================================================
     File: filename.html
     Developer: [Sundram/Suyash]
     Version: 1.0.0
     Description: Brief description of the file's purpose
     Created: 2026-03-17
     Last Modified: 2026-03-17
     Dependencies: [list dependencies]
     Notes: [any additional notes]
     ========================================================================= -->
```
#### CSS/JS Header
```css
/* ============================================================================
   File: filename.css
   Developer: [Sundram/Suyash]
   Version: 1.0.0
   Description: Brief description of the file's purpose
   Created: 2026-03-17
   Last Modified: 2026-03-17
   Dependencies: [list dependencies]
   Notes: [any additional notes]
   ============================================================================ */
```

---

### 🔄 Git Workflow
#### Initial Setup
```bash
git clone https://github.com/koushaljhacs/hostel-management-system-frontend.git
cd hostel-management-system-frontend

# Create your feature branch
git checkout -b feature/your-name-module
```
#### Daily Workflow
```bash
# Before starting work, pull latest changes
git checkout develop
git pull origin develop
git checkout your-feature-branch
git merge develop

# After completing work
git add .
git commit -m "type(scope): description"
git push origin your-feature-branch
```
#### Branch Naming Convention
- **Feature:** `feature/name-module` (e.g., `feature/sundram-patient-module`)
- **Bugfix:** `bugfix/name-issue` (e.g., `bugfix/sundram-login-error`)
- **Hotfix:** `hotfix/issue-description` (e.g., `hotfix/critical-security-patch`)

#### Commit Message Format
```text
type(scope): short description

Types: feat, fix, docs, style, refactor, test, chore
Scope: patient, doctor, pharmacy, lab, billing, admin, etc.

Examples:
- feat(patient): add patient dashboard HTML structure
- fix(auth): resolve login form validation
- docs(readme): update setup instructions
```

---

### 💻 VS Code Setup
#### Recommended Extensions
| Extension          | ID                                | Purpose                   |
| ------------------ | --------------------------------- | ------------------------- |
| Live Server        | `ritwickdey.LiveServer`           | Local development server  |
| Prettier           | `esbenp.prettier-vscode`          | Code formatting           |
| ESLint             | `dbaeumer.vscode-eslint`          | JavaScript linting        |
| HTML CSS Support   | `ecmel.vscode-html-css`           | CSS IntelliSense          |
| Path Intellisense  | `christian-kohler.path-intellisense`| Auto-complete file paths  |
| GitLens            | `eamodio.gitlens`                 | Git integration           |

#### Error Fix Commands
```bash
# Merge conflict resolution
git mergetool

# Reset if broken
git fetch --all
git reset --hard origin/develop

# Undo last commit but keep changes
git reset --soft HEAD~1

# Undo last commit and discard changes
git reset --hard HEAD~1

# Clean untracked files
git clean -fd
```
---

### 📊 Module Breakdown
| Module           | Files   | Developer |
| ---------------- | ------- | --------- |
| auth/            | 10      | Sundram   |
| public/          | 28      | Sundram   |
| patient/         | 47      | Sundram   |
| doctor/          | 40      | Sundram   |
| nurse/           | 28      | Sundram   |
| receptionist/    | 28      | Sundram   |
| pharmacist/      | 42      | Suyash    |
| lab-technician/  | 44      | Suyash    |
| radiologist/     | 28      | Suyash    |
| billing/         | 52      | Suyash    |
| admin/           | 67      | Suyash    |
| ground-staff/    | 28      | Shared    |
| security/        | 17      | Shared    |
| employee/        | 25      | Shared    |
| reports/         | 28      | Shared    |
| error/           | 12      | Shared    |
| components/      | 42      | Shared    |
| layouts/         | 15      | Shared    |
| root/            | 11      | Shared    |
| **TOTAL HTML**   | **584** |           |
| **CSS/JS/Assets**| **115** |           |
| **GRAND TOTAL**  | **699** |           |

---

### ⏰ Deadline
**Start Date:** 2026-03-17

**End Date:** 2026-04-12

**Total Duration:** 26 days

All 699 files must be completed and ready for API integration by the deadline.

---

### 🔗 Backend API
**Base URL:** `http://100.81.13.80`

**API Version:** `v1`

**Integration:** After frontend completion, backend team will integrate

---

### ❓ FAQ
**Q: Do we need to create all pages at once?**
A: No, follow the phased approach. Start with your assigned modules.

**Q: How do we handle API integration?**
A: Create mock data functions in `api.js` initially. Use `setTimeout` to simulate API calls.

**Q: What if we need new components?**
A: Create in `components/` folder and document in comments. Follow naming conventions.

**Q: How to handle responsive design?**
A: Mobile-first approach. Write base styles for mobile, then use media queries for tablet (768px+) and desktop (1024px+).

**Q: Where to get icons and images?**
A: Create placeholders first. Use SVG icons from FontAwesome or similar. Final assets will be provided later.

---

### 📄 License
Proprietary · © 2026 Koushal Jha. All rights reserved.

<p align="center">🏥 <strong>Hospital Management System - Frontend</strong> · Built with precision for API synchronization</p> 
