<div align="center">

  <!-- BANNIÈRE ANIMÉE DYNAMIQUE AUX COULEURS DU LOGO -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3C5D,100:00A896&height=220&section=header&text=LEHIE%20BIOMETRICS&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Clinical%20Statistical%20Programming%20%26%20Biostatistical%20Consulting&descAlignY=58&descSize=18" width="100%" alt="Lehie Biometrics Banner" />

  <br/>

  <!-- TITRE AVEC BADGE CARRÉ STYLE TWITTER/X -->
  <h2>
    Lehie Biometrics <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="28" height="28" align="absmiddle" alt="Verified Badge" />
  </h2>

  <p>
    <i><b>"Transforming complex clinical trial data into regulatory-grade evidence."</b></i><br/>
    <sub><b>FDA • EMA • PMDA Submission Standards | CDISC SDTM & ADaM | Phase I–IV</b></sub>
  </p>

  <!-- BADGES VISUELS PREMIUM AVEC ICÔNES -->
  <p>
    <img src="https://img.shields.io/badge/SAS_9.4_%7C_Viya-0B3C5D?style=for-the-badge&logo=sas&logoColor=white" alt="SAS" />
    <img src="https://img.shields.io/badge/R_Pharmaverse-00A896?style=for-the-badge&logo=r&logoColor=white" alt="R Pharmaverse" />
    <img src="https://img.shields.io/badge/CDISC-SDTM_%26_ADaM-1B263B?style=for-the-badge&logo=databricks&logoColor=00A896" alt="CDISC" />
    <img src="https://img.shields.io/badge/Pinnacle_21-100%25_Compliant-2E8B57?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Pinnacle 21" />
  </p>

  <p>
    <a href="mailto:lehie@gmx.fr">
      <img src="https://img.shields.io/badge/Contact_Studio-lehie%40gmx.fr-5E60CE?style=flat-square&logo=minutemailer&logoColor=white" alt="Email" />
    </a>
    <img src="https://img.shields.io/badge/Validation-Level_1_Double_Programming-0B3C5D?style=flat-square" alt="QC" />
    <img src="https://img.shields.io/badge/Focus-Oncology_%7C_Safety_%7C_Survival-00A896?style=flat-square" alt="Focus" />
  </p>

</div>

---

### 🏛️ L'Excellence Biométrique — **Lehie Biometrics** <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="18" height="18" align="absmiddle" />

**Lehie Biometrics** <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="16" height="16" align="absmiddle" /> est un studio d'ingénierie biostatistique et de programmation clinique dédié aux laboratoires pharmaceutiques, biotechs et CRO. Notre architecture repose sur un principe unique : **la double programmation croisée systématique (`SAS 9.4` $\leftrightarrow$ `R Pharmaverse`)** pour garantir une fiabilité mathématique absolue lors des soumissions réglementaires.

<br/>

<!-- CARTES VISUELLES CÔTE À CÔTE (HTML TABLE) -->
<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🧬 Standardisation CDISC & Architecture</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/SDTM_IG_v3.4-0B3C5D?style=flat-square" />
        <img src="https://img.shields.io/badge/ADaM_IG_v1.3-00A896?style=flat-square" />
        <img src="https://img.shields.io/badge/Define--XML_2.1-1B263B?style=flat-square" />
      </p>
      <ul>
        <li><b>Domaines SDTM :</b> Mapping automatisé (<code>DM</code>, <code>AE</code>, <code>RS</code>, <code>TR</code>, <code>LB</code>, <code>EX</code>) et gestion des domaines <code>SUPP--</code>.</li>
        <li><b>Datasets d'Analyse ADaM :</b> Architecture <code>ADSL</code>, <code>BDS</code> (<code>ADTTE</code>, <code>ADLB</code>) et <code>OCCDS</code> (<code>ADAE</code>, <code>ADCM</code>).</li>
        <li><b>Traçabilité Réglementaire :</b> Métadonnées conformes aux exigences <b>Pinnacle 21</b> (0 erreur, 0 warning non justifié).</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📊 Biostatistique & Restitution (TLF)</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/RECIST_1.1-8B0000?style=flat-square" />
        <img src="https://img.shields.io/badge/MedDRA_v27.0-0B3C5D?style=flat-square" />
        <img src="https://img.shields.io/badge/ICH_E3_CSR-00A896?style=flat-square" />
      </p>
      <ul>
        <li><b>Analyse de Survie (Oncologie) :</b> Courbes de Kaplan-Meier, IC de Brookmeyer-Crowley, Log-Rank stratifié et modèles de Cox (Efron).</li>
        <li><b>Tables ICH E3 Automatisées :</b> Démographie (14.1), Efficacité (14.2) et Tolérance par SOC/PT MedDRA et grade CTCAE (14.3).</li>
        <li><b>Double Programmation QC :</b> Réconciliation automatisée entre production <code>SAS</code> et validation indépendante <code>R</code> (<code>{diffdf}</code>).</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🔄 Architecture de Notre Pipeline Réglementaire

GitHub génère automatiquement ce diagramme interactif illustrant le flux de validation **Lehie Biometrics** <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="16" height="16" align="absmiddle" /> :

```mermaid
graph LR
    A[(EDC / Raw Data)] -->|Mapping & Specs| B(SDTM Domains<br/>DM, AE, RS, LB)
    B -->|SAS 9.4 Production| C[ADaM Prod<br/>ADSL, ADTTE, ADAE]
    B -->|R Pharmaverse {admiral}| D[ADaM Independent QC<br/>Level 1 Validation]
    C --> E{Automated Audit<br/>PROC COMPARE / diffdf}
    D --> E
    E -->|100% Equivalence| F[ICH E3 TLFs & CSR<br/>PROC REPORT / {rtables}]
    E -->|Pinnacle 21 Check| G([FDA / EMA eCTD Submission])

    style A fill:#1B263B,stroke:#00A896,stroke-width:2px,color:#fff
    style B fill:#0B3C5D,stroke:#00A896,stroke-width:2px,color:#fff
    style C fill:#0B3C5D,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#00A896,stroke:#fff,stroke-width:2px,color:#fff
    style E fill:#5E60CE,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#0B3C5D,stroke:#00A896,stroke-width:2px,color:#fff
    style G fill:#2E8B57,stroke:#fff,stroke-width:2px,color:#fff
