# Prometheus
*"god of forethought, the god of intelligence, a trickster, and as a champion of humanity"*<br>
Successor to Aurora, Prometheus is meant to simplify tracking of visits, successful petitions and opened emails into a single simple platform. This is meant to take away the complexities (behind the scenes) of Aurora make it easier to use / more reliable to maintain.

###Functions of Aurora:
- Successful petition tracking
- Page visit tracking
- Email opened tracking
- Campaign / Project / NRO / Regional differentiation

###Enhancements for Prometheus
- Google OAuth Sign-in

###DB Structure
*the tables and values stored here all imply uid's*<br>
- users
  - username
  - nro
- visits
  - surl
  - timestamp
- urls
  - surl
  - url
  - nro
  - campaign
  - project
  - country
  - language
- metadata
  - nro
    - name
  - campaign
    - name
  - project
    - name
  - country
    - code
    - name
  - language
    - code
    - name
  - project
  - country
  - language
