+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Senior Software Engineer"
  company = "SAP SuccessFactors"
  company_url = ""
  location = "Palo Alto, CA & Waldorf, Germany"
  date_start = "2014-03-31"
  date_end = ""
  description = """Responsible for requirement analysis, design, develop & automation of SuccessFactors Core HR utilized by 3000+ customers. 
  Responsibilities include:
  
  * Focus on end-to-end ownership, handling design, implementation, unit test, automation and, component delivery pipeline
  * Migrated application data model from server cache to distributed cache (Redis) with refactoring models for efficient network transfer
  * Designed and developed OData and Rest API for integrations and used messaging queue (Kafka) for inter-module PubSub model
  * Stabilized the product to guardrail the configurations that lead to application server bottlenecks, handled performance stabilization
  * Architecture backend test automation using propriety framework, resulting test case execution from several minutes to few seconds
  * Led team of five members and mentored them in achieving project timelines and help them to produce quality code-based standards
  * Used Test-driven development (TDD) and Agile practices to provide reliable and testable code
  """

[[experience]]
  title = "Professor"
  company = "Tech Mahindra"
  company_url = ""
  location = "San Ramon, California"
  date_start = "2011-04-01"
  date_end = "2014-03-28"
  description = """Responsible for requirement analysis, design, develop, migrate & performance test the P2P product “SAP Ariba” for Major Oil and Gas company spends 40 billion through direct and indirect spending on Ariba.
  Responsibilities include:
  * Part of data migration team that involved extracting and importing millions of various Ariba transactional objects
  * Designed and implemented custom extractions and importing into new object models (with most of the complexities like field type changes, field name changes, converting raw files to blobs, associating backward and forward object references)
  * Perfected the speed of extract and import using multi-threading and multi-servers
  * The migration objects involved Contract (Contract Workspace, Contract & Contract Request), Requisition, Purchase Order & Invoices
  * Architecture the complex task to handle accumulation of commitments, approvals, orders & actuals on different downstream objects
  """

+++
