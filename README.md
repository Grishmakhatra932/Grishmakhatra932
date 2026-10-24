<h1 align="center">Grishma Khatra</h1>

<p align="center">
  <strong>EDI & B2B Integration Specialist</strong><br>
  iPaaS · ERP · APIs · Trading Partner Onboarding
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/grishma-khatra">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn">
  </a>
  <a href="https://github.com/Grishmakhatra932">
    <img src="https://img.shields.io/badge/GitHub-Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="View GitHub projects">
  </a>
  <a href="https://www.credly.com/badges/84378d17-eb06-45bb-891b-cedc24a19a01/linked_in_profile">
    <img src="https://img.shields.io/badge/Boomi-Integration%20Developer%20Certificate-2F80ED?style=for-the-badge" alt="Boomi Integration Developer Certificate">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/60%2B-Customer%20%26%20Partner%20Onboardings-176B87?style=flat-square" alt="60+ combined customer and trading partner onboardings">
  <img src="https://img.shields.io/badge/Focus-EDI%20%7C%20ERP%20%7C%20API-176B87?style=flat-square" alt="EDI ERP and API integration focus">
  <img src="https://img.shields.io/badge/Location-Toronto%2C%20Canada-176B87?style=flat-square" alt="Toronto, Canada">
</p>

---

## About

I’m an integration professional with a **Master of Computer Science from Lakehead University** and hands-on experience connecting customer ERP and e-commerce systems with trading partners through a B2B iPaaS platform.

I work across the integration lifecycle: gathering requirements, configuring customer and partner connections, mapping business documents, validating transactions, and tracing failed or missing documents. I also use APIs and Postman to inspect customer ERP data during onboarding when direct ERP access isn’t available.

## Integration Flow

```mermaid
flowchart LR
    ERP["Customer ERP / Shopify"] --> Adapter["HubBroker adapter"]
    Adapter --> Mapping["Map, transform, validate"]
    Mapping --> Channel["AS2 / SFTP / PEPPOL / VAN"]
    Channel --> Partner["Trading partner"]
