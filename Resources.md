# Sources & Further Reading

This document collects the main sources and inspirations behind the *Homelab Naming Ideology* talk. It includes academic work on psychological ownership, books on motivation, enterprise naming standards, and practical homelab resources.

---

## 1. Psychology of ownership & engagement

- Pierce, J. L., Kostova, T., & Dirks, K. T. (2001).  
  “Toward a theory of psychological ownership in organizations.” *Academy of Management Review*, 26(2), 298–310.  
  – Foundational work on how feelings of ownership (including through naming) increase care, responsibility, and persistence.

- Pink, D. H. (2009).  
  *Drive: The Surprising Truth About What Motivates Us.* Riverhead Books.  
  – Explores autonomy, mastery, and purpose as drivers of sustained engagement in self‑directed projects like homelabs.

---

## 2. Enterprise naming standards & best practices

- RFC 952 – *Requirements for Internet Hosts – Application and Support.*  
  – Early guidance on host naming rules that still influences many naming standards.

- ISO/IEC 11582 and related IT standards.  
  – Broader context for structured naming and identifier conventions used in larger organizations.

- University of Alaska Anchorage – Device Naming Conventions  
  <https://www.uaa.alaska.edu/about/administrative-services/departments/information-technology-services/getting-help/knowledge-base/device-naming-conventions.cshtml>  
  – Concrete institutional standard showing how enterprises encode location, role, and other attributes into names.

- MOBS – *A Proper Server Device Naming Convention: Best Practices, Standard Naming Conventions and Framework Requirements*  
  <https://www.mobs-bd.org/a-proper-server-device-naming-convention-best-practices-standard-naming-conventions-and-framework-requirements/>  
  – High‑level best‑practices article on designing consistent naming conventions for servers and devices.

---

## 3. Homelab articles & community discussions

- r/homelab – *What’s your home lab server naming scheme?*
  <https://www.reddit.com/r/homelab/comments/wpxvo9/whats_your_home_lab_server_naming_scheme/>  
  – Large community thread with many real‑world naming patterns (themes, purposes, hybrids).

- Homelab.gdn – *Naming Things is Hard*
  <https://homelab.gdn/blog/naming-things-is-hard/>  
  – Blog post on practical and philosophical aspects of naming in personal infrastructure.

- ServeTheHome forums (general homelab discussions)
  – Community experience with evolving naming schemes as labs grow and roles change.

---

## 4. Service discovery, DNS, and device vs. service naming

- Tailscale Documentation  
  <https://tailscale.com/>  
  – Documentation and examples relevant to separating **device identity** from **service endpoints** using coordination tools and DNS.

- mDNS / DNS‑SD (DNS Service Discovery)  
  – Standards and implementations supporting zero‑configuration discovery and service naming in local networks.

These resources informed the talk’s recommendation to keep creative or hybrid names at the device level while exposing stable, purpose‑driven names at the service layer (e.g. `backup.home.ts.net`, `auth.home.ts.net`).

---

## 5. Inspiration from homelab practice

- r/homelab (general) – <https://www.reddit.com/r/homelab/>  
- ServeTheHome – <https://forums.servethehome.com/>  

These communities provide many practical examples of:

- Theming hosts (mythology, astronomy, birds, etc.).
- Mixing physical descriptors with fun names for better recall.
- Gradually adding structure as homelabs grow and automation increases.

