# Orbital Tumor RT — Target Delineation Skill

Radiotherapy target volume delineation and dose constraints for orbital tumors — lymphoma, solid malignancies, and benign entities.

## What This Skill Does

The orbit is the most OAR-dense region in radiation oncology. This skill provides a standardized decision chain:

1. **Three-compartment localization** — intraocular vs orbital vs extraorbital
2. **Extraorbital lymphatic cascade** — VIII→IX→IIa (often missed by ophthalmologists)
3. **Compartment-based irradiation** — not distance-based margins
4. **Door and next room** — orbital apex (the door) + cavernous sinus (the next room)
5. **Anterior segment co-management** — cornea, lacrimal gland, nasolacrimal duct

## Quick Install

### Hermes Agent
```bash
hermes skills install https://raw.githubusercontent.com/antica1/orbital-tumor-rt-targets/master/SKILL.md
```

### Claude Code
Copy `SKILL.md` into your Claude skills directory.

## Trigger Keywords

`orbital tumor` `eye tumor` `ocular lymphoma` `lacrimal gland` `sebaceous carcinoma` `retinoblastoma` `uveal melanoma` `orbital radiotherapy`

## Key References

- 中国眼及附属器肿瘤放射治疗指南（2021版）. 中国医师协会放疗专委会.
- Pinnix CC et al. *JAMA Oncol* 2024 (PMID:38990564) — Ultralow-dose orbital RT
- ILROG Guidelines. *IJROBP* 2021
- QUANTEC / AAPM TG-101

## Author

Zhu Guopei, MD — Department of Radiation Oncology, Shanghai Ninth People's Hospital, Shanghai Jiao Tong University School of Medicine.  
Contact: antica@gmail.com

## License

MIT
