# Graph Report - .  (2026-06-18)

## Corpus Check
- Large corpus: 244 files · ~1,717,179 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 1010 nodes · 1401 edges · 96 communities (50 shown, 46 thin omitted)
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 95 edges (avg confidence: 0.81)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Full Test Suite|Full Test Suite]]
- [[_COMMUNITY_Dashboard Pipeline View|Dashboard Pipeline View]]
- [[_COMMUNITY_Job Portal Scanners|Job Portal Scanners]]
- [[_COMMUNITY_Salary Filtering & Ashby|Salary Filtering & Ashby]]
- [[_COMMUNITY_Tracker Merge Logic|Tracker Merge Logic]]
- [[_COMMUNITY_Internationalization & CV Sync|Internationalization & CV Sync]]
- [[_COMMUNITY_Dashboard UI Models|Dashboard UI Models]]
- [[_COMMUNITY_Deduplication & Matching|Deduplication & Matching]]
- [[_COMMUNITY_Dashboard Data Logic|Dashboard Data Logic]]
- [[_COMMUNITY_Follow-up Cadence|Follow-up Cadence]]
- [[_COMMUNITY_Dashboard Document Viewer|Dashboard Document Viewer]]
- [[_COMMUNITY_Liveness Checker|Liveness Checker]]
- [[_COMMUNITY_Pipeline Health Checks|Pipeline Health Checks]]
- [[_COMMUNITY_PDF & Cover Letter Generation|PDF & Cover Letter Generation]]
- [[_COMMUNITY_AI Evaluation (Gemini)|AI Evaluation (Gemini)]]
- [[_COMMUNITY_Rejection Pattern Analysis|Rejection Pattern Analysis]]
- [[_COMMUNITY_System Updater|System Updater]]
- [[_COMMUNITY_System Setup & Diagnostics|System Setup & Diagnostics]]
- [[_COMMUNITY_SQLite Tracker Index|SQLite Tracker Index]]
- [[_COMMUNITY_Portal Configuration Validator|Portal Configuration Validator]]
- [[_COMMUNITY_Dashboard Progress Stats|Dashboard Progress Stats]]
- [[_COMMUNITY_LaTeX CV Builder|LaTeX CV Builder]]
- [[_COMMUNITY_Updater Migration Tests|Updater Migration Tests]]
- [[_COMMUNITY_Tracker Schema Tests|Tracker Schema Tests]]
- [[_COMMUNITY_Local Job Parser|Local Job Parser]]
- [[_COMMUNITY_Application Status Normalizer|Application Status Normalizer]]
- [[_COMMUNITY_Evaluation & Scoring Core|Evaluation & Scoring Core]]
- [[_COMMUNITY_SmartRecruiters Provider|SmartRecruiters Provider]]
- [[_COMMUNITY_Arabic & Portuguese Modes|Arabic & Portuguese Modes]]
- [[_COMMUNITY_Candidate Profiles & Evaluations|Candidate Profiles & Evaluations]]
- [[_COMMUNITY_Project Scaffolder CLI|Project Scaffolder CLI]]
- [[_COMMUNITY_Dashboard Career Model|Dashboard Career Model]]
- [[_COMMUNITY_Greenhouse Provider|Greenhouse Provider]]
- [[_COMMUNITY_Workable Provider|Workable Provider]]
- [[_COMMUNITY_Recruitee Provider|Recruitee Provider]]
- [[_COMMUNITY_Tracker Lock Mechanism|Tracker Lock Mechanism]]
- [[_COMMUNITY_SolidJobs Provider|SolidJobs Provider]]
- [[_COMMUNITY_Project Roadmap Phases|Project Roadmap Phases]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 50|Community 50]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 55|Community 55]]
- [[_COMMUNITY_Community 56|Community 56]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 63|Community 63]]
- [[_COMMUNITY_Community 64|Community 64]]
- [[_COMMUNITY_Community 65|Community 65]]
- [[_COMMUNITY_Community 66|Community 66]]
- [[_COMMUNITY_Community 67|Community 67]]
- [[_COMMUNITY_Community 68|Community 68]]
- [[_COMMUNITY_Community 69|Community 69]]
- [[_COMMUNITY_Community 70|Community 70]]
- [[_COMMUNITY_Community 71|Community 71]]
- [[_COMMUNITY_Community 72|Community 72]]
- [[_COMMUNITY_Community 73|Community 73]]
- [[_COMMUNITY_Community 74|Community 74]]
- [[_COMMUNITY_Community 75|Community 75]]
- [[_COMMUNITY_Community 76|Community 76]]
- [[_COMMUNITY_Community 77|Community 77]]
- [[_COMMUNITY_Community 78|Community 78]]
- [[_COMMUNITY_Community 79|Community 79]]
- [[_COMMUNITY_Community 80|Community 80]]
- [[_COMMUNITY_Community 81|Community 81]]
- [[_COMMUNITY_Community 82|Community 82]]
- [[_COMMUNITY_Community 83|Community 83]]
- [[_COMMUNITY_Community 84|Community 84]]
- [[_COMMUNITY_Community 85|Community 85]]
- [[_COMMUNITY_Community 86|Community 86]]
- [[_COMMUNITY_Community 87|Community 87]]
- [[_COMMUNITY_Community 88|Community 88]]
- [[_COMMUNITY_Community 89|Community 89]]
- [[_COMMUNITY_Community 90|Community 90]]
- [[_COMMUNITY_Community 91|Community 91]]
- [[_COMMUNITY_Community 92|Community 92]]
- [[_COMMUNITY_Community 93|Community 93]]
- [[_COMMUNITY_Community 94|Community 94]]
- [[_COMMUNITY_Community 95|Community 95]]

## God Nodes (most connected - your core abstractions)
1. `PipelineModel` - 38 edges
2. `NewTheme()` - 25 edges
3. `ViewerModel` - 18 edges
4. `NewPipelineModel()` - 18 edges
5. `main()` - 13 edges
6. `ProgressModel` - 12 edges
7. `main()` - 11 edges
8. `analyze()` - 11 edges
9. `main()` - 11 edges
10. `ParseApplications()` - 11 edges

## Surprising Connections (you probably didn't know these)
- `main()` --calls--> `parseArgs()`  [INFERRED]
  generate-cover-letter.mjs → scan-ats-full.mjs
- `rowToMarkdown()` --calls--> `clean`  [INFERRED]
  tracker.mjs → verify-pipeline.mjs
- `makeSandbox()` --calls--> `tmpDir`  [INFERRED]
  tracker-columns-tests.mjs → test-all.mjs
- `resolveTrackerLockDir()` --calls--> `tmpDir`  [INFERRED]
  merge-tracker.mjs → test-all.mjs
- `runSelfTest()` --calls--> `tmpDir`  [INFERRED]
  validate-portals.mjs → test-all.mjs

## Hyperedges (group relationships)
- **System Onboarding Flow** — agents_onboarding, cv_markdown, portals_configuration [EXTRACTED 1.00]
- **Community Governance Structure** — governance_bdfl_model, governance_contributor_ladder, code_of_conduct_standards [EXTRACTED 1.00]
- **Core User Data Files** — user_layer, cv_txt [EXTRACTED 0.90]
- **Job Search Automation Flow** — portal_scanner, evaluation_pipeline, batch_processing, ats_optimized_cv [EXTRACTED 0.95]
- **Modes Architecture** — modes_oferta, modes_auto_pipeline, modes_apply, modes_pipeline [EXTRACTED 0.90]
- **Internationalized Modes** — modes_tr_is_ilani, modes_tr_basvuru, modes_ua_pipeline, modes_ua_interview_prep [EXTRACTED 0.95]
- **Localization of Career-Ops Modes** — ua__shared, ru__shared, ar__shared, pt__shared [INFERRED 0.90]
- **Localized Evaluation Workflows** — ua_oferta, ru_oferta, ar_fursah, pt_oferta, fr_offre [INFERRED 0.95]
- **Example Data Suite** — cv_example_alexchen, article_digest_example_fraudshield, sample_report_evaluationreportformat, ats_normalization_test_atsnormalization [INFERRED 0.85]
- **Lim Chee Kin's AI Projects** — profile_open_text_embeddings, profile_project_concord, profile_talk_to_ai, profile_rag_wtf [INFERRED 1.00]
- **Forward Deployed Engineer Roles** — 001_elevenlabs_2026_06_17_elevenlabs, 011_langchain_2026_06_17_langchain, 025_bland_2025_05_22_bland_ai [INFERRED 0.95]
- **Project Roadmap Flow** — roadmap_phases_now, roadmap_phases_next, roadmap_phases_later [EXTRACTED 1.00]
- **Press and Visibility Assets** — wired_logo_wired, business_insider_logo_bi, producthunt_badge_ph [INFERRED 0.85]

## Communities (96 total, 46 thin omitted)

### Community 0 - "Full Test Suite"
Cohesion: 0.01
Nodes (155): a, absPathResult, activePolishPosting, activeWorkdayPage, additionsA, additionsB, additionsDir, adsRows (+147 more)

### Community 1 - "Dashboard Pipeline View"
Cohesion: 0.07
Nodes (20): now, StatusPriority(), colWidths, formatTimeAgo(), matchesSearch(), previewOutcome(), statusLabel(), truncateRunes() (+12 more)

### Community 2 - "Job Portal Scanners"
Cohesion: 0.09
Nodes (37): appendToPipeline(), appendToScanHistory(), loadCompanyList(), main(), parallelEach(), parseArgs(), SOURCES, buildLocationFilter() (+29 more)

### Community 3 - "Salary Filtering & Ashby"
Cohesion: 0.05
Nodes (38): blankBoth, blankMin, boolCurrency, bothZero, filter, hourlyJob, infResult, invertedFilter (+30 more)

### Community 4 - "Tracker Merge Logic"
Cohesion: 0.05
Nodes (30): addition, app, appContent, appLines, APPS_FILE, before, CANONICAL_STATES, CAREER_OPS (+22 more)

### Community 5 - "Internationalization & CV Sync"
Cohesion: 0.05
Nodes (36): content, cvContent, cvPath, digestPath, __dirname, errors, filesToCheck, lines (+28 more)

### Community 6 - "Dashboard UI Models"
Cohesion: 0.1
Nodes (31): main(), NewPipelineModel(), previewModelWith(), tabIndexForFilter(), TestEscWithoutQueryIsNoOp(), TestPreviewKeepsDiscardReasonWhenTlDrIsCached(), TestPreviewOutcomeForStatusWithoutNotes(), TestPreviewOutcomeOmittedForActiveApps() (+23 more)

### Community 7 - "Deduplication & Matching"
Cohesion: 0.07
Nodes (29): app, bestStatusRank, CAREER_OPS, cluster, content, DRY_RUN, entries, extractReportNum() (+21 more)

### Community 8 - "Dashboard Data Logic"
Cohesion: 0.1
Nodes (24): appModel, viewState, batchEntry, cleanTableCell(), ComputeMetrics(), ComputeProgressMetrics(), enrichAppURLsByCompany(), enrichFromScanHistory() (+16 more)

### Community 9 - "Follow-up Cadence"
Cohesion: 0.11
Nodes (27): ACTIONABLE_STATUSES, addDays(), ALIASES, analyze(), appliedDaysIdx, args, CADENCE, CAREER_OPS (+19 more)

### Community 10 - "Dashboard Document Viewer"
Cohesion: 0.14
Nodes (11): inlineMatch, detectAlignment(), findInlineMatch(), isHeadingLine(), isSpecialBlockLine(), isTableLine(), isTableSeparator(), NewViewerModel() (+3 more)

### Community 11 - "Liveness Checker"
Cohesion: 0.15
Nodes (24): main(), CHALLENGE_CODES, checkUrlLiveness(), checkUrlLivenessWithFallback(), createHeadedPageProvider(), extractMappedIPv4(), isChallengeResult(), jitteredDelayMs() (+16 more)

### Community 12 - "Pipeline Health Checks"
Cohesion: 0.07
Nodes (22): ADDITIONS_DIR, ALIASES, CANONICAL_STATUSES, CAREER_OPS, clean, companyRoleMap, content, entries (+14 more)

### Community 13 - "PDF & Cover Letter Generation"
Cohesion: 0.15
Nodes (24): asUrl(), buildAchievementsBlock(), buildContactLine(), buildCredentialsBlock(), buildDateline(), buildFootnotesBlock(), buildHtml(), escapeHtml() (+16 more)

### Community 14 - "AI Evaluation (Gemini)"
Cohesion: 0.08
Nodes (20): args, companySlug, cvContent, genAI, mergeOutput, model, normalizedTrackerScore(), num (+12 more)

### Community 15 - "Rejection Pattern Analysis"
Cohesion: 0.11
Nodes (19): ALIASES, analyze(), args, CAREER_OPS, classifyOutcome(), extractBlockerType(), MACHINE_SUMMARY_FIELDS, minThresholdIdx (+11 more)

### Community 16 - "System Updater"
Cohesion: 0.17
Nodes (20): addPaths(), apply(), check(), compareVersions(), curlGet(), dashboardGoSourcesChanged(), __dirname, extractArrayFromSource() (+12 more)

### Community 17 - "System Setup & Diagnostics"
Cohesion: 0.15
Nodes (21): argv, checkAutoDir(), checkDependencies(), checkFonts(), checkNodeVersion(), checkPlaywright(), checkPlaywrightMcp(), checkPrereq() (+13 more)

### Community 18 - "SQLite Tracker Index"
Cohesion: 0.26
Nodes (18): COMMANDS, ensureFresh(), exportMd(), flagValue(), history(), loadSqlite(), loadStates(), mdHash() (+10 more)

### Community 19 - "Portal Configuration Validator"
Cohesion: 0.3
Nodes (14): add(), formatIssue(), isObject(), loadProviderIds(), main(), normalizeName(), PROVIDERS_DIR, ROOT (+6 more)

### Community 20 - "Dashboard Progress Stats"
Cohesion: 0.2
Nodes (3): NewProgressModel(), ProgressClosedMsg, ProgressModel

### Community 21 - "LaTeX CV Builder"
Cohesion: 0.29
Nodes (12): buildEducation(), buildExperience(), buildProjects(), buildSkills(), __dirname, escapeLatex(), main(), runSelfTest() (+4 more)

### Community 22 - "Updater Migration Tests"
Cohesion: 0.2
Nodes (11): allowedSystemUserOverlap, bootstrapPaths, extractArray(), fail(), overlapsUserPath, pass(), requiredBootstrapPaths, requiredSystemPaths (+3 more)

### Community 23 - "Tracker Schema Tests"
Cohesion: 0.18
Nodes (6): merge, res, ROOT, row, sb, verify

### Community 24 - "Local Job Parser"
Cohesion: 0.31
Nodes (10): buildParserArgs(), detect(), execFileAsync, expandParserArg(), fetch(), getParserScriptPath(), normalizeJobUrl(), normalizeLocation() (+2 more)

### Community 25 - "Application Status Normalizer"
Cohesion: 0.2
Nodes (8): CAREER_OPS, content, DRY_RUN, lines, num, parts, result, unknowns

### Community 26 - "Evaluation & Scoring Core"
Cohesion: 0.2
Nodes (10): A-F Scoring System, ATS-Optimized CV, Batch Worker Prompt, Batch Processing, Batch README, Career-Ops Project, Cover Letter Generator, Candidate CV (Text) (+2 more)

### Community 27 - "SmartRecruiters Provider"
Cohesion: 0.36
Nodes (9): ALLOWED_SMARTRECRUITERS_HOSTS, assertSmartRecruitersUrl(), buildPostingsUrl(), detect(), fetch(), parseSmartRecruitersResponse(), resolveApiUrl(), resolveSlug() (+1 more)

### Community 28 - "Arabic & Portuguese Modes"
Cohesion: 0.22
Nodes (9): AR Shared Context, AR Fursah Mode, AR Takdeem Mode, Arab Market Specifics, Block G: Posting Legitimacy, Brazil Market Specifics, PT Shared Context, PT Aplicar Mode (+1 more)

### Community 29 - "Candidate Profiles & Evaluations"
Cohesion: 0.29
Nodes (8): ElevenLabs, Evaluation: ElevenLabs — Forward Deployed Engineer, LangChain, Lim Chee Kin, open-text-embeddings, Project Concord, RAG.WTF, Talk To AI

### Community 30 - "Project Scaffolder CLI"
Cohesion: 0.39
Nodes (6): detectClis(), die(), has(), latestTag(), main(), SUPPORTED_CLIS

### Community 31 - "Dashboard Career Model"
Cohesion: 0.29
Nodes (6): CareerApplication, FunnelStage, PipelineMetrics, ProgressMetrics, ScoreBucket, WeekActivity

### Community 32 - "Greenhouse Provider"
Cohesion: 0.48
Nodes (5): ALLOWED_GREENHOUSE_HOSTS, assertGreenhouseUrl(), detect(), fetch(), resolveApiUrl()

### Community 33 - "Workable Provider"
Cohesion: 0.48
Nodes (6): ALLOWED_WORKABLE_HOSTS, assertWorkableUrl(), detect(), fetch(), parseWorkableMarkdown(), resolveFeedUrl()

### Community 34 - "Recruitee Provider"
Cohesion: 0.6
Nodes (5): assertRecruiteeUrl(), detect(), fetch(), parseRecruiteeResponse(), resolveApiUrl()

### Community 35 - "Tracker Lock Mechanism"
Cohesion: 0.4
Nodes (5): acquireTrackerLock(), lockCanRecover(), processIsAlive(), readLockOwner(), sleep()

### Community 36 - "SolidJobs Provider"
Cohesion: 0.5
Nodes (3): ALLOWED_HOSTS, assertUrl(), fetch()

### Community 37 - "Project Roadmap Phases"
Cohesion: 0.83
Nodes (4): Later: Desktop App for Everyone, Next: Free Local AI, Now: Community & Foundation, Roadmap Phases Diagram

### Community 38 - "Community 38"
Cohesion: 0.5
Nodes (4): latexValidate(), parse(), tmpDir, makeSandbox()

### Community 39 - "Community 39"
Cohesion: 0.5
Nodes (4): fail(), log, pass(), warn()

### Community 40 - "Community 40"
Cohesion: 0.67
Nodes (3): MINDEF - Singapore, Mistral AI, Sovereign AI

### Community 41 - "Community 41"
Cohesion: 0.67
Nodes (3): Project Origin, Gemini CLI Integration, OpenCode Integration

### Community 42 - "Community 42"
Cohesion: 0.67
Nodes (3): FraudShield Project, Hero Metrics, LLM Eval Toolkit Project

### Community 43 - "Community 43"
Cohesion: 0.67
Nodes (3): Community Standards, BDFL Governance Model, Contributor Ladder

### Community 44 - "Community 44"
Cohesion: 0.67
Nodes (3): Onboarding Process, CV Markdown Source, Portals Configuration

### Community 45 - "Community 45"
Cohesion: 0.67
Nodes (3): Data Contract, System Layer, User Layer

### Community 46 - "Community 46"
Cohesion: 0.67
Nodes (3): challengePage(), fakePage(), livePage()

## Knowledge Gaps
- **481 isolated node(s):** `systemPaths`, `userPaths`, `bootstrapPaths`, `requiredSystemPaths`, `requiredBootstrapPaths` (+476 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **46 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `parse()` connect `Community 38` to `Full Test Suite`, `Dashboard Data Logic`, `Dashboard UI Models`?**
  _High betweenness centrality (0.161) - this node is a cross-community bridge._
- **Why does `main()` connect `Dashboard UI Models` to `Dashboard Data Logic`, `Community 38`?**
  _High betweenness centrality (0.152) - this node is a cross-community bridge._
- **Why does `tmpDir` connect `Community 38` to `Full Test Suite`, `Portal Configuration Validator`, `Community 53`?**
  _High betweenness centrality (0.148) - this node is a cross-community bridge._
- **Are the 24 inferred relationships involving `NewTheme()` (e.g. with `.Update()` and `main()`) actually correct?**
  _`NewTheme()` has 24 INFERRED edges - model-reasoned connections that need verification._
- **Are the 15 inferred relationships involving `NewPipelineModel()` (e.g. with `main()` and `TestWithReloadedDataPreservesStateAndSelection()`) actually correct?**
  _`NewPipelineModel()` has 15 INFERRED edges - model-reasoned connections that need verification._
- **What connects `systemPaths`, `userPaths`, `bootstrapPaths` to the rest of the system?**
  _481 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Full Test Suite` be split into smaller, more focused modules?**
  _Cohesion score 0.01 - nodes in this community are weakly interconnected._