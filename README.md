<div align="center">

  <br/>

  <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="110" height="110" alt="Lehie Biometrics Official Emblem" />

  <h1>
    LEHIE BIOMETRICS <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="26" height="26" align="absmiddle" alt="Official Badge" />
  </h1>

  <p>
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&duration=3200&pause=1000&color=00A896&center=true&vCenter=true&width=780&lines=CLINICAL+STATISTICAL+PROGRAMMING+%26+BIOSTATISTICAL+CONSULTING;CDISC+SDTM+IG+3.4+%26+ADaM+IG+1.3+REGULATORY+ARCHITECTURE;LEVEL-1+DOUBLE+PROGRAMMING+%3A+SAS+9.4+%26+R+PHARMAVERSE;FDA+%E2%80%A2+EMA+%E2%80%A2+PMDA+SUBMISSION-READY+CLINICAL+DELIVERABLES" alt="Animated Technical Tagline" />
  </p>

  <p>
    <img src="https://img.shields.io/badge/SAS_9.4_%7C_VIYA-PRODUCTION-0B3C5D?style=for-the-badge&logo=sas&logoColor=white" alt="SAS" />
    <img src="https://img.shields.io/badge/R_PHARMAVERSE-VALIDATION_QC-00A896?style=for-the-badge&logo=r&logoColor=white" alt="R Pharmaverse" />
    <img src="https://img.shields.io/badge/CDISC-SDTM_%26_ADaM-1B263B?style=for-the-badge" alt="CDISC" />
    <img src="https://img.shields.io/badge/PINNACLE_21-COMPLIANT-2E8B57?style=for-the-badge" alt="Pinnacle 21" />
  </p>

  <p>
    <a href="mailto:lehie@gmx.fr">
      <img src="https://img.shields.io/badge/CONTACT_DIRECTION-lehie%40gmx.fr-0B3C5D?style=flat-square" alt="Email" />
    </a>
    <img src="https://img.shields.io/badge/METHODOLOGY-ICH_E3_%7C_E9_(R1)-1B263B?style=flat-square" alt="ICH" />
    <img src="https://img.shields.io/badge/THERAPEUTIC_FOCUS-ONCOLOGY_(RECIST_1.1)_%26_SAFETY-00A896?style=flat-square" alt="Focus" />
  </p>

</div>

---

### I. PRÉSENTATION DU STUDIO

**Lehie Biometrics** <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="16" height="16" align="absmiddle" /> est une structure indépendante de programmation statistique clinique et d'ingénierie biostatistique. Nous concevons des pipelines de données d'essais cliniques (Phases I à IV) soumis aux standards réglementaires internationaux (**FDA, EMA, PMDA**).

Notre protocole d'assurance qualité repose sur la **double programmation indépendante inter-langages (Validation de Niveau 1)** : chaque jeu de données d'analyse produit sous **SAS 9.4** est intégralement contre-programmé sous **R (écosystème Pharmaverse)** et audité mathématiquement avant soumission.

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">INGÉNIERIE & STANDARDISATION CDISC</h4>
      <p align="center">
        <img src="https://img.shields.io/badge/SDTM_IG_v3.4-0B3C5D?style=flat-square" />
        <img src="https://img.shields.io/badge/ADaM_IG_v1.3-00A896?style=flat-square" />
        <img src="https://img.shields.io/badge/Define--XML_v2.1-1B263B?style=flat-square" />
      </p>
      <ul>
        <li><b>Domaines SDTM :</b> Spécifications de mapping et dérivation des domaines d'intervention, d'événements et de résultats (<code>DM</code>, <code>AE</code>, <code>RS</code>, <code>TR</code>, <code>TU</code>, <code>LB</code>, <code>EX</code>).</li>
        <li><b>Modèles d'Analyse ADaM :</b> Architecture <code>ADSL</code>, structures <code>BDS</code> (<code>ADTTE</code>, <code>ADLB</code>, <code>ADRS</code>) et structures d'occurrence <code>OCCDS</code> (<code>ADAE</code>, <code>ADCM</code>).</li>
        <li><b>Conformité eCTD :</b> Contrôle d'intégrité des métadonnées, formats <code>XPT v5</code> et justification documentée (SDRG / ADRG) sous <b>Pinnacle 21</b>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">MODÉLISATION BIOSTATISTIQUE & TLF</h4>
      <p align="center">
        <img src="https://img.shields.io/badge/RECIST_v1.1-8B0000?style=flat-square" />
        <img src="https://img.shields.io/badge/MedDRA_v27.0-0B3C5D?style=flat-square" />
        <img src="https://img.shields.io/badge/CTCAE_v5.0-00A896?style=flat-square" />
      </p>
      <ul>
        <li><b>Analyse de Survie :</b> Estimateur de Kaplan-Meier, intervalles de confiance de Brookmeyer-Crowley, test du Log-Rank stratifié et modèle de Cox (gestion des ex-aequo d'Efron).</li>
        <li><b>Restitution Réglementaire (ICH E3) :</b> Production automatisée de Tables, Listings et Figures (Sections 14.1, 14.2 et 14.3) prêts pour l'intégration CSR.</li>
        <li><b>Réconciliation Automatisée :</b> Audit croisé systématique via <code>PROC COMPARE</code> (SAS) et <code>diffdf</code> (R) avec tolérance numérique stricte ($10^{-8}$).</li>
      </ul>
    </td>
  </tr>
</table>

---

### II. ARCHITECTURE INTERACTIVE DU PIPELINE RÉGLEMENTAIRE

*Utilisez le panneau de contrôle intégré en haut à droite du schéma pour zoomer et naviguer dans l'architecture de validation **Lehie Biometrics** <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="15" height="15" align="absmiddle" /> :*

```mermaid
flowchart LR
    subgraph S1 ["1. INGESTION & STANDARDISATION"]
        A[("Bases Cliniques EDC<br/>RAW / CRF")] -->|"Mapping Specs"| B["Domaines SDTM v3.4<br/>DM, AE, RS, LB, EX"]
    end

    subgraph S2 ["2. DOUBLE PROGRAMMATION CROISÉE (NIVEAU 1)"]
        B -->|"Moteur Production"| C["SAS 9.4 Production<br/>ADSL, ADTTE, ADAE"]
        B -->|"Moteur Validation"| D["R Pharmaverse (admiral)<br/>Independent QC Datasets"]
        C --> E{"Audit Mathématique<br/>PROC COMPARE / diffdf"}
        D --> E
    end

    subgraph S3 ["3. LIVRABLES RÉGLEMENTAIRES"]
        E -->|"100% Match"| F["Sorties CSR (ICH E3)<br/>PROC REPORT & rtables"]
        E -->|"Validation Métadonnées"| G(["Soumission FDA / EMA<br/>Pinnacle 21 & Define-XML"])
    end

    style A fill:#1B263B,stroke:#00A896,stroke-width:2px,color:#fff
    style B fill:#0B3C5D,stroke:#00A896,stroke-width:2px,color:#fff
    style C fill:#0B3C5D,stroke:#ffffff,stroke-width:2px,color:#fff
    style D fill:#00A896,stroke:#ffffff,stroke-width:2px,color:#fff
    style E fill:#1B263B,stroke:#00A896,stroke-width:2px,color:#fff
    style F fill:#0B3C5D,stroke:#00A896,stroke-width:2px,color:#fff
    style G fill:#2E8B57,stroke:#ffffff,stroke-width:2px,color:#fff
```

---

### III. INSPECTION TECHNIQUE INTERACTIVE

*Cliquez sur les barres ci-dessous pour déployer et inspecter nos standards de code et de validation directement depuis cette page :*

<details>
<summary><b>[DÉPLOYER] 1. Aperçu comparatif : Programmation de la Survie Sans Progression (SAS 9.4 vs R Pharmaverse)</b></summary>
<br/>

```sas
/* --- PRODUCTION SAS 9.4 : Modèle de Cox Stratifié & Kaplan-Meier (Extrait) --- */
proc phreg data=adam.adtte(where=(ittfl="Y" and paramcd="PFS" and anl01fl="Y"));
    class trt01pn(ref="0") strat1 strat2;
    model aval*cnsr(1, 2, 3) = trt01pn / ties=efron rl alpha=0.05;
    strata strat1 strat2;
    ods output ParameterEstimates=_cox_hr;
run;
```

```r
# --- VALIDATION INDÉPENDANTE R : Dérivation ADTTE via {admiral} & Audit {diffdf} ---
qc_comparison <- diffdf::diffdf(
  base      = prod_adtte,
  compare   = qc_adtte,
  keys      = c("STUDYID", "USUBJID", "PARAMCD"),
  tolerance = 1e-8
)
```

</details>

<details>
<summary><b>[DÉPLOYER] 2. Matrice Réglementaire de Censure FDA en Oncologie (ADaM.ADTTE - RECIST 1.1)</b></summary>
<br/>

| Scénario Clinique | Date d'Analyse (`ADT`) | `CNSR` | Description (`EVNTDESC`) | Source (`SRCDOM.SRCVAR`) |
| :--- | :--- | :---: | :--- | :--- |
| **Absence d'évaluation tumorale** et pas de décès | `ADSL.RANDDT` | `2` | No Baseline or Post-Baseline Assessment | `ADSL.RANDDT` |
| **Nouveau traitement anti-cancéreux (`NACTDT`)** avant progression | `LASTTUDT` avant `NACTDT` | `3` | New Anti-Cancer Therapy Prior to Event | `RS.RSDTC` |
| **Progression radiologique documentée (`PD`)** ou Décès | `min(PDDT, DTHDT)` | `0` | Disease Progression or Death | `RS.RSDTC` / `ADSL.DTHDT` |
| **En cours de suivi sans événement** à la date de cut-off | `LASTTUDT` | `1` | Alive and Progression-Free at Cut-Off | `RS.RSDTC` |

</details>

<details>
<summary><b>[DÉPLOYER] 3. Extrait de Rapport de Réconciliation Automatisée Niveau 1 (SAS Production vs R QC)</b></summary>
<br/>

```text
================================================================================
LEHIE BIOMETRICS — AUTOMATED LEVEL 1 DOUBLE PROGRAMMING QC REPORT
================================================================================
Dataset Validated : ADaM.ADTTE (Time-to-Event Analysis Dataset)
Production Engine : SAS 9.4 TS1M7 (programs/01_sas_prod/adtte_prod.sas)
Validation Engine : R 4.4.1 / {admiral} 1.1.0 (programs/02_r_qc/v_adtte_qc.R)
Key Variables     : STUDYID, USUBJID, PARAMCD
Numeric Tolerance : 1.00e-08
Execution Status  : PASS (0 Discrepancies Found across 200 subjects x 23 cols)
================================================================================
FINAL VERDICT: [LEHIE BIOMETRICS QC PASS] - 100% Equivalence Confirmed.
================================================================================
```

</details>

---

### IV. RÉPERTOIRES DE PRODUCTION (FEATURED REPOSITORIES)

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>
        <a href="https://github.com/lehie-biometrics/cdisc-oncology-adtte-pipeline">01. cdisc-oncology-adtte-pipeline</a>
      </h4>
      <p>
        <b>Oncologie Phase III (RECIST 1.1) — Dérivation <code>ADaM.ADTTE</code> & Analyse de Survie (PFS)</b>
      </p>
      <ul>
        <li>Implémentation complète de la hiérarchie de censure <b>FDA Oncology Guidance</b>.</li>
        <li>Estimation de Kaplan-Meier (IC de Brookmeyer-Crowley), test du Log-Rank stratifié et modèle de Cox sous <code>SAS 9.4</code>.</li>
        <li>Double programmation indépendante sous <code>R {admiral}</code> et audit automatisé <code>{diffdf}</code>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/SAS_9.4-PRODUCTION-0B3C5D?style=flat-square" />
        <img src="https://img.shields.io/badge/R_ADMIRAL-LEVEL_1_QC_PASS-00A896?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>
        <a href="https://github.com/lehie-biometrics/cdisc-safety-adae-tlf-engine">02. cdisc-safety-adae-tlf-engine</a>
      </h4>
      <p>
        <b>Tolérance Clinique (Safety) — Dérivation <code>ADaM.ADAE</code> & Tables Réglementaires ICH E3 14.3.1</b>
      </p>
      <ul>
        <li>Programmation des indicateurs d'événements émergents (<code>TRTEMFL</code>) et des flags de première occurrence (<code>AOCCIFL</code>, <code>AOCCSIFL</code>, <code>AOCCPIFL</code>).</li>
        <li>Algorithmes d'imputation conservatrice des dates partielles d'événements indésirables.</li>
        <li>Restitution hiérarchique par SOC/PT <b>MedDRA v27.0</b> et grade <b>CTCAE v5.0</b> via <code>PROC REPORT</code> et <code>R {rtables}</code>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/SAS_9.4-OCCDS_COMPLIANT-0B3C5D?style=flat-square" />
        <img src="https://img.shields.io/badge/R_RTABLES-CSR_READY-00A896?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### V. MATRICE DES TECHNOLOGIES & STANDARDS

<div align="center">

| Domaine Technique | Spécifications & Environnements Déployés par **Lehie Biometrics** <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="15" height="15" align="absmiddle" /> |
| :--- | :--- |
| **Moteurs Statistiques** | `SAS 9.4 (TS1M7)` • `SAS Viya` • `R (4.4+)` • `PROC SQL / SQL` • `Python` |
| **Écosystème R Pharmaverse** | `{admiral}` • `{admiralonco}` • `{rtables}` • `{tern}` • `{gt}` • `{diffdf}` • `{sdtm.oak}` • `{haven}` |
| **Procédures SAS Cliniques** | `PROC LIFETEST` • `PROC PHREG` • `PROC MIXED` • `PROC GENMOD` • `PROC REPORT` • `PROC SGPLOT` • `PROC COMPARE` |
| **Normes & Terminologies** | `CDISC SDTM IG 3.4` • `ADaM IG 1.3` • `Define-XML 2.1` • `MedDRA v27.0` • `WHO Drug` • `NCI-CTCAE v5.0` • `RECIST v1.1` |

</div>

---

<div align="center">

  <h4>DIRECTION BIOMÉTRIQUE & COLLABORATION</h4>
  <p>
    Disponible pour les opérations de programmation statistique clinique, de sous-traitance biométrique (CRO / Industrie Pharmaceutique) et d'audit CDISC.<br/><br/>
    <b>LEHIE BIOMETRICS</b> <img src="https://raw.githubusercontent.com/lehie-biometrics/lehie-biometrics/main/logo.png" width="16" height="16" align="absmiddle" /> — <i>Montpellier & Toulouse, France</i><br/>
    <b>Contact Officiel :</b> <a href="mailto:lehie@gmx.fr"><b>lehie@gmx.fr</b></a>
  </p>

</div>
