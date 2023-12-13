# DopCHECK
├── README.md
├── LICENSE.md
├── INSTALL.md
├── src
│   ├── P1
│   ├── P1_PP_processing.py
│   │       ├── text_preprocessing.py  
│   │        <!-- paragraph level -->
│   │       ├── find_subtitle.py
│   │       │ 	├── paragraph_bayesian.py
│   │       ├── types_pp_processing.py
│   │        <!-- sentence level -->
│   │       │   ├── sentence_bayesian.py
│   │       │   ├── phrase_similarity.py
│   │       ├── children_pp_processing.py
│   │       ├── region_pp_processing.py
│   │       ├── retention_pp_processing.py
│   ├── P2
│   │	├── test_case_execution.py
│   │       ├── echo_spider.py
│   ├── P3
│       ├── behavior_log_process.py
│           ├── noncompliance_check.py
│           ├── utilities.py
├── dataset
│	├── SkillExplorer_log
│	├── training_data
│	    ├── title.csv
│	    ├── personal_type.csv
├── example
│   ├── CHILDREN_example
│   ├── REGIONS_example
│   ├── RETENTION_example
│   ├── TYPES_example
│   ├── pp_example
├── benchmark
│   ├── benchmark_log_type
│   ├── benchmark_log_child
│   ├── benchmark_log_region
│   ├── benchmark_log_retention
└── library
    └── chromedriver