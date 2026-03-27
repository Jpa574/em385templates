# Heyron Skills

This repository contains skill packages that extend Heyron's capabilities for USACE construction QAR work.

## Skills Available

### usace-qar
USACE Quality Assurance Representative skills for MILCON and civil works projects.

**What's included:**
- 17 UFGS trade specifications (concrete, steel, electrical, HVAC, etc.)
- 6 project phases (Design Review → Closeout)
- Safety knowledge (OSHA 1926, EM 385-1-1)
- AHA review and development
- QC program documentation
- Multi-role thinking (PE, Super, QC, SSHO)

**Files:**
- `skills/usace-qar/SKILL.md` - Main skill definition
- `skills/usace-qar/references/` - Supporting reference documents
- `skills/usace-qar/usace-qar.skill` - Packaged skill file

## How to Use

1. Clone this repository
2. Skills are in the `skills/` folder
3. Each skill has its own folder with SKILL.md and references/

## Building Skills

To package a skill:
```bash
python3 /path/to/skill-creator/scripts/package_skill.py skills/usace-qar
```

## Validation

All knowledge is validated against official USACE sources:
- EM 385-1-1 (Safety Manual)
- EP 415-1-261 (QAR Guide Series)
- UFGS (Unified Facilities Guide Specifications)
- OSHA 1926 (Construction Safety Regulations)

See `skills/usace-qar/references/Validated-Sources.md` for full source list.