# Rithujaa Portfolio - Project Guidelines

## Project Overview
Senior-level Data Engineering portfolio website with modern, minimal design targeting US tech hiring standards.

## Design Philosophy
- **Senior-level aesthetic**: Confident, minimal, professional
- **Modern SaaS style**: Clean, breathable, intentional
- **NOT**: Dashboard UI, bootcamp project, over-designed or flashy
- **Dark theme**: Consistent throughout

---

## "Tools I Work With" Section - Design Specifications

### 1. Objective
Redesign the technical skills section to:
- Remove large card containers
- Remove dashboard-style layout
- Replace with dynamic, filterable skill grid
- Maintain dark theme consistency
- Feel polished and senior-level (not student portfolio style)

### 2. Section Structure

#### Header
- **Title**: "Tools I Work With"
- Apply subtle gradient accent to "work with"
- **Optional subtitle** (small, muted text):
  > "Technologies I use to build scalable data systems."
- **Spacing**: Generous top and bottom padding, clear visual separation from adjacent sections

### 3. Filter Navigation

#### Layout
- Position filter buttons horizontally above the tool grid
- **Filters**:
  - All (default active)
  - Cloud
  - Orchestration
  - Languages
  - DevOps
  - Architecture

#### Style
- Rounded pill buttons
- Minimal design
- No heavy borders
- Subtle glow or filled background when active
- Smooth animated transition between active states
- Maintain category color consistency

#### Behavior
- **Default filter**: All
- **Clicking a filter**:
  - Smooth fade-out of non-matching tools
  - Smooth fade-in + slight upward motion of matching tools
  - No layout shift
  - Animation duration: 200–300ms
  - Easing: smooth (ease-in-out)

### 4. Tool Grid Layout

#### Structure
- Responsive auto-wrap grid:
  - Desktop: 4–6 tools per row
  - Tablet: 3–4 tools per row
  - Mobile: 2 per row
- No boxed containers
- Each tool displayed as:
  - Rounded pill tag
  - Tool name only (no emoji icons)
  - Subtle colored border or glow based on category

### 5. Category Color System

Maintain subtle color coding:
- **Cloud** → Purple accent
- **Orchestration** → Teal accent
- **Languages** → Amber accent
- **DevOps** → Blue accent
- **Architecture** → Violet accent

Color usage should be:
- Subtle
- Refined
- Not oversaturated

### 6. Motion & Micro-Interactions

#### On Scroll Into View
- Staggered fade-up animation
- Slight delay between rows
- Smooth and professional

#### On Hover (Tool Pills)
- Slight scale: max 1.03
- Glow intensifies slightly
- Smooth 200ms transition
- Cursor pointer

#### On Filter Change
- Fade out old tools
- Fade in new tools
- Slight vertical motion
- No snapping or abrupt transitions

**Animations should feel premium and subtle, not flashy.**

### 7. Visual Hierarchy
- Tool pills slightly more prominent than filter buttons
- Consistent spacing between pills
- Generous whitespace throughout
- No heavy dividers
- No large bordered containers
- The section should feel breathable and intentional

### 8. Scalability Requirements
- Tools rendered from structured data array
- Unlimited tool support
- Automatic layout reflow
- Adding new tools should not require layout changes

### 9. Accessibility
- Keyboard navigable filter buttons
- Visible focus states
- Proper ARIA attributes
- Respect `prefers-reduced-motion` settings

### 10. Technical Guidance

**If using React**:
- Preferred: Framer Motion for animation
- Alternative: CSS transitions (lightweight)

**Requirements**:
- No layout shift
- High performance
- Clean modular component structure

### 11. Design Outcome Target

The final result should feel:
- ✅ Senior-level data engineering portfolio
- ✅ Modern SaaS aesthetic
- ✅ Built for US tech hiring standards
- ✅ Confident and minimal

It should NOT feel:
- ❌ Like a dashboard UI
- ❌ Like a bootcamp project
- ❌ Over-designed or flashy

---

## Tools List by Category

### Cloud
- AWS S3
- AWS Lambda
- AWS EC2
- AWS Glue
- Azure Data Factory
- ADLS Gen2
- Databricks
- Azure Synapse
- Snowflake

### Orchestration
- Apache Airflow
- Apache Spark
- PySpark
- Apache Kafka
- Snowpipe
- Apache NiFi
- Streams & Tasks
- DAG Orchestration

### Languages
- Python
- SQL
- R
- PySpark
- Pandas

### DevOps
- Git
- Docker
- PostgreSQL
- Tableau

### Architecture
- ETL Pipelines
- Data Warehousing
- Lakehouse
- Data Modeling
- Streaming
- Batch Processing
- CDC
- Cross-functional Teams
- ML Integration
- Dashboard Design
- Agile

---

## General Development Notes
- Maintain consistent spacing and typography throughout
- All animations should respect user motion preferences
- Keep code modular and maintainable
- Test responsive behavior across all breakpoints
