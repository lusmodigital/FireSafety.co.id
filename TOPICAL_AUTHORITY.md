# Topical Authority — FireSafety.co.id

## Role and boundary

FireSafety.co.id should become an Indonesian fire-safety knowledge hub that helps building owners, facility teams, designers, contractors, workers, and occupants understand fire risk across prevention, detection, containment, suppression, evacuation, inspection, and recovery.

The domain may cover the same subjects as other Syamsul-owned domains. Cross-domain overlap is allowed; cannibalization control in this plan applies only among pages on FireSafety.co.id.

Safety boundary: articles educate and support informed procurement, but do not replace a site-specific design, fire-risk assessment, authority inspection, manufacturer instruction, or work by a competent fire-protection professional. Exact legal and standard requirements must be checked against the current official text and local rules before publication.

## Evidence audited

Audit date: 2026-07-23.

| Evidence | Finding |
|---|---|
| Repository | Static HTTrack-era mirror on `main`; no content CMS or article collection |
| HTML inventory | 31 HTML files below the mirrored domain directory |
| Usable pages | The homepage contains commercial copy and navigation signals |
| Failed snapshots | 30 HTML files render as `404 Not Found`; they are not valid editorial coverage |
| Intended legacy subjects | APAR and media variants, thermatic extinguisher, alarm, hydrant/box/pillar/valve, sprinkler, APAR installation/refill/maintenance, and PPE/safety equipment |
| Sitemap | No usable sitemap XML is present; `sitemap.go` is only an XML URL-rewrite utility |
| URL risk | Legacy commercial routes exist outside `/artikel/`; planned editorial slugs use `/artikel/<slug>/` to avoid direct collisions |

Primary planning references to verify during drafting:

- [PP No. 16 Tahun 2021 on building implementation](https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-)
- [Permen PU No. 26/PRT/M/2008 on fire protection for buildings and environments](https://peraturan.bpk.go.id/Details/104475/permen-pupr-no-26prtm2008-tahun-2008)
- [Permen PU No. 20/PRT/M/2009 on urban fire-protection management](https://peraturan.bpk.go.id/Details/104492/permen-pupr-no-)
- [BSN fire-protection catalog, including current sprinkler, pump, and detection standards](https://pesta.bsn.go.id/produk/by_ics/35?ics_no=13&key=)

Permenaker No. PER.04/MEN/1980 and Kepmenaker No. KEP.186/MEN/1999 should be retrieved from an official JDIH copy before quoting requirements. Local regulations can add inspection and administrative procedures; the correct city/regency rule must be checked for location-specific content.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Thin commercial homepage; only usable page | expand | Commercial overview linked to knowledge hubs | Confirm current offer, company identity, service area, and contact |
| `/apar/` and `/apar/*.html` | Intended product taxonomy but mirrored as 404 | manual review | FS-03 and future product routes | Check deployed URLs and any backlink/history before redirects |
| `/pasang-apar.html` | Intended APAR placement/service route; 404 snapshot | manual review | Commercial route plus FS-04 education | Check indexation/backlinks and current service |
| `/maintenance-apar.html` | Intended service route; 404 snapshot | manual review | Commercial route plus FS-05 education | Check whether service remains offered |
| `/refill-apar.html` | Intended refill route; 404 snapshot | manual review | Commercial route plus FS-05 education | Verify terminology, service process, and warranty |
| `/alarm.html` | Intended fire-alarm route; 404 snapshot | manual review | FS-06/FS-07 and a separate commercial route | Inspect live URL and historical links |
| `/fire-hydrant/` and children | Intended hydrant product taxonomy; all 404 snapshots | manual review | FS-08/FS-09 | Verify product/service scope and link history |
| `/fire-sprinkler/` | Intended sprinkler route; 404 snapshot | manual review | FS-10 | Verify whether design/installation is offered |
| `/alat-safety*` | Mixed fire/PPE catalog; 404 snapshots | split | FS-18 for firefighting PPE; general PPE stays commercial/supporting | Do not imply all PPE is fire-rated |
| `/blog/`, feeds, comments feeds | Empty/failed archive artifacts | noindex or remove | New `/artikel/` hub | Verify deployed behavior before removal |

Main risks:

- safety claims becoming prescriptive without a site assessment;
- outdated standard numbers or local rules being presented as universal;
- APAR, hydrant, sprinkler, and alarm pages mixing selection, installation, maintenance, and sales intent;
- multiple “jenis alat pemadam” pages competing for the same query;
- generic location-swapped service pages becoming doorway content;
- synthetic case studies or inspection claims without field evidence.

## Coverage matrix

| Completeness lens | Topic owners | Status/notes |
|---|---|---|
| Vocabulary, fire science, measurements | FS-00, FS-01 | Covered |
| Types, parts, and system architecture | FS-02 through FS-12 | Covered |
| Need recognition and risk assessment | FS-01, FS-15, FS-19 | Covered |
| Design and selection | FS-03, FS-06 through FS-14, FS-19 | Covered |
| Procurement and cost | FS-20 | Covered |
| Installation and commissioning | FS-04, FS-07 through FS-12, FS-21 | Covered |
| Operation and occupant action | FS-04, FS-13, FS-16 | Covered |
| Inspection and maintenance | FS-05, FS-21 | Covered |
| Troubleshooting and failure | FS-05 through FS-12, FS-21 | Covered inside system-specific briefs |
| Upgrade and replacement | FS-05, FS-07, FS-21, FS-23 | Covered |
| Safety and health | FS-00, FS-04, FS-13, FS-18 | Covered |
| Regulation and evidence | FS-02 and each technical topic | Covered with mandatory source verification |
| Building/use-case context | FS-19 | Covered |
| Geography and climate | FS-22 | Covered without place-name doorway pages |
| Environmental effects | FS-03, FS-11, FS-15, FS-23 | Covered |
| Emerging risks | FS-23 | Covered |
| Post-incident lifecycle | FS-17 | Covered |
| History | FS-00-A06 in catalog | Covered as one article; a separate parent topic is unnecessary |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| FS-00 | Dasar api dan keselamatan kebakaran | Understand the language and mechanisms needed to interpret later guidance | fire triangle/tetrahedron; heat transfer; ignition; flashover/backdraft; smoke and toxic gases; fire growth; extinguishing mechanisms; terminology; history | sourced diagrams; glossary; expert review | Fundamentals only; hazard assessment belongs to FS-01 and system selection to FS-03/FS-06-FS-12 | 6 |
| FS-01 | Klasifikasi bahaya dan asesmen risiko | Recognize hazards and structure a defensible initial risk assessment | fire classes; fuel/load; ignition sources; occupancy; vulnerable users; probability/consequence; survey evidence; risk register; change management | risk matrix; walkthrough checklist; documented examples | Does not prescribe final system design; compliance framework is FS-02 and building scenarios are FS-19 | 6 |
| FS-02 | Regulasi, standar, dan kepatuhan | Find and interpret the hierarchy of national, local, workplace, and technical requirements | PP/Permen/Permenaker/local rules; SNI/ISO/NFPA roles; PBG/SLF context; authority inspections; document control; edition checks | primary legal links; standards register; compliance flowchart | Never quote unverified clauses; system technical explanations remain in their owner topics | 6 |
| FS-03 | Pemilihan APAR dan media pemadam | Select an extinguisher family based on hazard and limitations | water; foam; dry chemical powder; CO2; clean agent; wet chemical; ratings; size/capacity; residue; electrical and cooking risks; environmental/health trade-offs | decision table; manufacturer data comparison; expert review | Placement/use is FS-04; maintenance/refill is FS-05; fixed systems are FS-08-FS-12 | 6 |
| FS-04 | Penempatan dan penggunaan APAR | Make APAR reachable and know when/how a trained person may use it | travel/access; mounting/signage; visibility; obstruction; PASS-like sequence; escape-first decision; wind/smoke; failed discharge; training props | placement diagram; decision tree; safety stop conditions | Does not determine legal quantities without verified assessment; servicing belongs to FS-05 | 6 |
| FS-05 | Inspeksi, maintenance, refill, dan umur APAR | Keep extinguisher inventory traceable and identify service/replacement needs | visual checks; pressure/seals/hose/corrosion; weighing; records/tags; refill; hydrostatic testing concepts; counterfeit servicing; discharge/leak response; end of life | inspection checklist; service records; manufacturer instructions | Does not teach unsafe cylinder work; product selection belongs to FS-03 | 6 |
| FS-06 | Deteksi kebakaran | Choose and understand detectors without confusing technologies | smoke/heat/flame/gas/multisensor; detection principles; nuisance alarms; spacing concept; environment; aspirating/beam detection; testing | detector comparison; application matrix; verified standards | Control panels, notification, cause-and-effect are FS-07 | 6 |
| FS-07 | Alarm, notifikasi, dan kendali | Understand how alarm inputs become actionable warnings and control outputs | conventional/addressable; panel/zones/loops; manual call points; bells/sounders/strobes/voice; monitoring; cause-effect; false alarm; accessibility; records | system block diagram; cause-effect matrix; test checklist | Detector physics is FS-06; evacuation behavior is FS-13 | 6 |
| FS-08 | Hidran, standpipe, hose reel, dan jaringan pipa | Understand the distribution system and component roles | yard hydrant; standpipe; hose reel; pillar/valve/box/hose/nozzle; siamese/FDC; zoning; pressure concepts; pipe/valve condition; use limitations | anatomy diagrams; component table; inspection walkdown | Water source and pumps are FS-09; firefighter operations require competent teams | 6 |
| FS-09 | Pasokan air dan pompa kebakaran | Understand reliability of water storage, supply, and pump arrangements | tank/source; duty/standby/jockey roles; electric/diesel; suction/discharge; controllers; flow/pressure testing; churn; impairment; fuel/battery; drainage | schematic; test curves; log template; standards verification | Distribution is FS-08 and sprinkler design is FS-10; no site sizing without calculations | 6 |
| FS-10 | Sprinkler otomatis | Understand sprinkler operation, design inputs, inspection, and common myths | thermal operation; wet/dry/preaction/deluge; hazard classification; heads/orifices/temperature; obstruction; valves; acceptance; inspection; accidental activation | system diagrams; myth table; current SNI register | Water supply is FS-09; special agents are FS-11; no spacing/design values without verified standard | 6 |
| FS-11 | Sistem pemadaman khusus | Compare fixed suppression for hazards that water/APAR may not suit | kitchen wet chemical; foam; clean agent; water mist; CO2 fixed systems; server/electrical rooms; machinery; enclosure integrity; personnel risk; discharge aftermath | application matrix; sequence diagram; safety review | General APAR is FS-03; sprinkler is FS-10; detailed design requires specialists | 6 |
| FS-12 | Proteksi kebakaran pasif | Preserve compartmentation and structural performance | fire-rated walls/floors/doors; penetrations/firestop; shafts; dampers; joints; structural protection; labels; inspection after renovation; facade spread | detail diagrams; photo defect atlas; product-system evidence | Active detection/suppression stays FS-06-FS-11; evacuation route use is FS-13/FS-14 | 6 |
| FS-13 | Evakuasi dan perilaku penghuni | Help organizations plan safe movement and account for human behavior | escape-first principle; roles; route familiarity; assistance; accountability; assembly; drills; panic myths; blocked route decisions; children/elderly/disabled users | evacuation flow; drill observer sheet; scenario exercises | Physical exit design and smoke/lighting systems are FS-14; emergency command is FS-16 | 6 |
| FS-14 | Sarana jalan keluar, asap, dan pencahayaan darurat | Understand the building features that keep evacuation tenable | exits; travel path concept; stairs; doors; emergency lighting; exit signs; smoke barriers; pressurization; smoke exhaust; refuge/accessibility; testing | annotated plans; inspection checklist; verified code references | Behavior/drills are FS-13; passive compartment construction is FS-12 | 6 |
| FS-15 | Pencegahan sumber penyalaan | Control common causes before a protection system is needed | electrical overload/loose connections; LPG/fuel; hot work; smoking; housekeeping; cooking; charging/batteries; static; arson/security interface; permit-to-work | control hierarchy; permit checklist; thermal-image examples | System response belongs to FS-03-FS-11; emerging-energy detail is FS-23 | 6 |
| FS-16 | Manajemen darurat dan organisasi | Build repeatable readiness, roles, communication, and continuity | emergency response plan; fire warden/team; command structure; training; drills; impairment plan; contractor control; shift coverage; mutual aid; records | RACI; drill calendar; response-plan template | Personal evacuation is FS-13; post-fire recovery is FS-17 | 6 |
| FS-17 | Sesudah kebakaran | Act safely after extinguishment and preserve evidence/recovery options | re-entry control; hidden heat/re-ignition; utilities; authority/insurer notification; evidence; cleanup hazards; smoke/water damage; salvage; lessons learned; continuity | recovery checklist; incident timeline; expert interviews | Not a substitute for official investigation or structural clearance; prevention updates link back to FS-01/FS-16 | 6 |
| FS-18 | APD dan peralatan petugas | Distinguish fire-service PPE and support equipment from generic safety products | helmets/gloves/boots/clothing; respiratory protection/SCBA; escape hoods; flashlights/tools; selection limits; inspection; contamination; retirement; competency | PPE matrix; inspection cards; manufacturer certifications | Does not imply ordinary occupants should fight fires; APAR use is FS-04 | 6 |
| FS-19 | Proteksi menurut fungsi bangunan | Translate occupancy and process differences into questions for a competent design | homes; apartments/hotels; hospitals; schools; offices/malls; warehouses; factories; kitchens; data rooms; heritage/high-rise; vulnerable occupants | scenario matrices; stakeholder checklists; expert review | Provides requirement questions, not universal layouts or quantities; technical systems retain their owner topics | 6 |
| FS-20 | Biaya, pengadaan, dan vendor | Compare proposals on scope, evidence, lifecycle value, and accountability | survey scope; BOQ; design vs supply/install; product certification; substitutions; warranty; maintenance contracts; hidden costs; tender comparison; red flags | bid comparison sheet; lifecycle-cost model; document checklist | No fabricated prices or vendor rankings; technical selection remains in system topics | 6 |
| FS-21 | Commissioning, inspeksi, dan integrasi sistem | Verify that installed systems work together and stay available | submittals; as-built; acceptance; integrated testing; cause-effect; impairment; inspection frequencies; defect severity; change control; audit trail | commissioning dossier; integrated-test matrix; defect register | System-specific tests stay in FS-05-FS-12; exact criteria require current standards and competent personnel | 6 |
| FS-22 | Iklim, lokasi, dan akses pemadam di Indonesia | Account for conditions that materially change protection and maintenance | humidity; corrosion/coast; flooding; seismic restraint; power reliability; dense settlements; water availability; traffic/access; local authority variation; remote sites | climate-risk matrix; local-rule research template; access diagrams | No city-swapped pages; publish local content only with substantive local evidence | 6 |
| FS-23 | Risiko dan teknologi baru | Prepare for changing energy systems and monitoring without hype | lithium-ion; EV charging; solar PV; energy storage; smart/connected detection; remote monitoring; cybersecurity; drones/robots; low-carbon agents; changing evidence | incident synthesis; technology matrix; primary research/standards | Treat uncertain evidence as evolving; conventional fundamentals remain FS-00-FS-22 | 6 |

## Related-domain opportunities

Other owned domains may independently publish the same topics. That is allowed and is not treated as cannibalization. Useful viewpoints include:

- `safety.co.id`: broader occupational safety, with FireSafety.co.id providing the fire-specific deep dive.
- `elevator.co.id`: elevator behavior, firefighter lifts, recall, and evacuation boundaries.
- `genset.co.id`/`generator-set` projects: emergency power and fuel risks.
- `kaca.co.id`, `fasad.co.id`, `partisi.co.id`, and material domains: tested assemblies, facade spread, fire doors, partitions, and penetrations.
- `hvac-r.id`: dampers, smoke control, shutdown logic, and kitchen exhaust risks.

Each domain can own its own complete article. Cross-links should be added only when editorially useful and not used as a substitute for coverage on FireSafety.co.id.

## Consolidation plan

1. Verify live response, index status, backlinks, and traffic for every legacy route before redirecting.
2. Preserve commercial routes when the service/product still exists; rewrite them as focused landing pages.
3. Place neutral education under `/artikel/` and link it contextually to commercial routes.
4. Use one APAR hub to connect selection (FS-03), placement/use (FS-04), and service lifecycle (FS-05).
5. Replace empty blog/feed artifacts with a useful article hub; noindex or remove archive pages that add no discovery value.
6. Do not create product pages for unavailable brands or certifications.

## Internal-link architecture

- `/artikel/` is the knowledge index.
- Each FS topic becomes a hub linking to all six child briefs.
- FS-00 and FS-01 feed every system-selection journey.
- FS-02 links to system pages where the regulation applies; system pages link back to the compliance register.
- FS-03-FS-12 form the equipment/system layer.
- FS-13-FS-17 form the people, management, and incident lifecycle.
- FS-19 routes readers by building type to the relevant systems without duplicating their technical explanations.
- FS-20 and commercial pages receive contextual links from decision and inspection pages.
- FS-21 closes the loop from every installed system to commissioning, inspection, and impairment management.
- FS-22/FS-23 modify the core guidance for environment and emerging risks rather than replacing it.

No article may be orphaned. Related links in the catalog are starting edges, not a fixed widget.

## Evidence and editorial standards

- Link to the official legal database and verify the regulation's status on the publication date.
- Confirm SNI title, edition, status, and scope in BSN's official catalog; obtain the full text where exact requirements are stated.
- Separate national building rules, workplace rules, local rules, standards, manufacturer instructions, and professional judgment.
- Require competent expert review for life-safety design, inspection intervals, extinguishing-agent suitability, occupancy requirements, and emergency instructions.
- Use original diagrams, labelled field photographs, test records, and anonymized real defects whenever possible.
- Never fabricate case studies, certifications, test results, incident causes, or price data.
- Put immediate-life-safety actions and stop conditions before SEO copy.
- Date-stamp regulation, technology, price, and incident-analysis articles.

## First bounded publication cluster

Publish 12 assets as Wave 1:

1. FS-00-A01 fire triangle/tetrahedron.
2. FS-00-A03 fire growth, flashover, and backdraft.
3. FS-01-A01 fire classes and fuel examples.
4. FS-01-A04 a building fire-risk walkthrough.
5. FS-02-A01 Indonesian fire-safety regulation map.
6. FS-03-A01 extinguisher media decision guide.
7. FS-03-A05 extinguisher rating/capacity interpretation.
8. FS-04-A01 placement survey.
9. FS-04-A03 decision to fight or evacuate.
10. FS-05-A01 monthly visual inspection checklist.
11. FS-05-A04 refill/service evidence guide.
12. FS-19-A01 home fire-protection questions.

This creates a coherent path from fire fundamentals to risk, compliance, APAR selection, safe action, and maintenance. Monitor indexation, impressions by intent, same-domain query overlap, checklist use, internal-link traversal, and qualified APAR/service inquiries. Expand the next system only after these pages contain reviewed evidence.

## Definition of done

- All 24 parent topics have six distinct article briefs in `ARTICLE_CATALOG.md`.
- Every proposed ID, title, and slug is unique within FireSafety.co.id.
- Each brief has one primary intent, a concrete outcome, and an explicit exclusion.
- All related IDs resolve and every topic has a hub/spoke path.
- Existing and proposed routes are checked for collisions before implementation.
- Safety-critical claims cite current primary sources and receive competent review.
- Legacy URLs have evidence-backed keep/merge/redirect decisions.
- A new sitemap includes only canonical, indexable pages after content is implemented.
