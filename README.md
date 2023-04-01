# EuroMov DHM LLOD Knowledge Extractor


## Full evaluation report from paper
```"DescriptiveStatisticsEvaluator": {
    "Termsuite REST": {
      "num_entities": 3092,
      "num_mentions": 31904,
      "num_mappings": 0,
      "avg_len": 12.46862871927555,
      "num_relations": 1369,
      "unique_sources": 531,
      "unique_targets": 787,
      "num_relation_types": 2
    },
    "Text2TCS ELG": {
      "num_entities": 10053,
      "num_mentions": 477783,
      "num_mappings": 0,
      "avg_len": 12.428429324579728,
      "num_relations": 28844,
      "unique_sources": 247,
      "unique_targets": 244,
      "num_relation_types": 9
    },
    "Entity Fishing": {
      "num_entities": 288,
      "num_mentions": 3558,
      "num_mappings": 0,
      "avg_len": 13.059027777777779,
      "num_relations": 281,
      "unique_sources": 130,
      "unique_targets": 59,
      "num_relation_types": 43
    },
    "Spotlight": {
      "num_entities": 572,
      "num_mentions": 4515,
      "num_mappings": 0,
      "avg_len": 15.183566433566433,
      "num_relations": 3484,
      "unique_sources": 484,
      "unique_targets": 351,
      "num_relation_types": 102
    },
    "NCBO Annotator": {
      "num_entities": 31829,
      "num_mentions": 54105,
      "num_mappings": 0,
      "avg_len": 7.534418297778755,
      "num_relations": 0,
      "unique_sources": 0,
      "unique_targets": 0,
      "num_relation_types": 0
    },
    "USEA Annotator": {
      "num_entities": 31354,
      "num_mentions": 33764,
      "num_mappings": 0,
      "avg_len": 12.0,
      "num_relations": 0,
      "unique_sources": 0,
      "unique_targets": 0,
      "num_relation_types": 0,
      "semantic_roles": 5255,
      "amr_graphs": 4591
    }
  },
  "OverlapEvaluator": {
    "Termsuite REST_vs_Text2TCS ELG": {
      "total_Termsuite REST": "3092",
      "total_Text2TCS ELG": "10053",
      "common (%Termsuite REST %Text2TCS ELG)": "1488 (0.48 0.15)",
      "common_partial_Termsuite REST_leq_Text2TCS ELG (%Text2TCS ELG)": "6771 (0.67)",
      "common_partial_Text2TCS ELG_leq_Termsuite REST (%Termsuite REST)": "618 (0.20)",
      "specific_Termsuite REST (%Termsuite REST)": "0 (0.00)",
      "specific_Text2TCS ELG (%Text2TCS ELG)": "1176 (0.12)",
      "relations with shared source+target (%Termsuite REST %Text2TCS ELG)": "0 (0.00 0.00)"
    },
    "Termsuite REST_vs_Entity Fishing": {
      "total_Termsuite REST": "3092",
      "total_Entity Fishing": "288",
      "common (%Termsuite REST %Entity Fishing)": "155 (0.05 0.54)",
      "common_partial_Termsuite REST_leq_Entity Fishing (%Entity Fishing)": "39 (0.14)",
      "common_partial_Entity Fishing_leq_Termsuite REST (%Termsuite REST)": "91 (0.03)",
      "specific_Termsuite REST (%Termsuite REST)": "2807 (0.91)",
      "specific_Entity Fishing (%Entity Fishing)": "3 (0.01)",
      "relations with shared source+target (%Termsuite REST %Entity Fishing)": "0 (0.00 0.00)"
    },
    "Termsuite REST_vs_Spotlight": {
      "total_Termsuite REST": "3092",
      "total_Spotlight": "572",
      "common (%Termsuite REST %Spotlight)": "254 (0.08 0.44)",
      "common_partial_Termsuite REST_leq_Spotlight (%Spotlight)": "76 (0.13)",
      "common_partial_Spotlight_leq_Termsuite REST (%Termsuite REST)": "57 (0.02)",
      "specific_Termsuite REST (%Termsuite REST)": "2705 (0.87)",
      "specific_Spotlight (%Spotlight)": "185 (0.32)",
      "relations with shared source+target (%Termsuite REST %Spotlight)": "0 (0.00 0.00)"
    },
    "Termsuite REST_vs_NCBO Annotator": {
      "total_Termsuite REST": "3092",
      "total_NCBO Annotator": "31829",
      "common (%Termsuite REST %NCBO Annotator)": "3 (0.00 0.00)",
      "common_partial_Termsuite REST_leq_NCBO Annotator (%NCBO Annotator)": "0 (0.00)",
      "common_partial_NCBO Annotator_leq_Termsuite REST (%Termsuite REST)": "6 (0.00)",
      "specific_Termsuite REST (%Termsuite REST)": "3083 (1.00)",
      "specific_NCBO Annotator (%NCBO Annotator)": "31820 (1.00)"
    },
    "Termsuite REST_vs_USEA Annotator": {
      "total_Termsuite REST": "3092",
      "total_USEA Annotator": "31354",
      "common (%Termsuite REST %USEA Annotator)": "2213 (0.72 0.07)",
      "common_partial_Termsuite REST_leq_USEA Annotator (%USEA Annotator)": "837 (0.03)",
      "common_partial_USEA Annotator_leq_Termsuite REST (%Termsuite REST)": "611 (0.20)",
      "specific_Termsuite REST (%Termsuite REST)": "0 (0.00)",
      "specific_USEA Annotator (%USEA Annotator)": "27693 (0.88)"
    },
    "Text2TCS ELG_vs_Entity Fishing": {
      "total_Text2TCS ELG": "10053",
      "total_Entity Fishing": "288",
      "common (%Text2TCS ELG %Entity Fishing)": "252 (0.03 0.88)",
      "common_partial_Text2TCS ELG_leq_Entity Fishing (%Entity Fishing)": "50 (0.17)",
      "common_partial_Entity Fishing_leq_Text2TCS ELG (%Text2TCS ELG)": "1091 (0.11)",
      "specific_Text2TCS ELG (%Text2TCS ELG)": "8660 (0.86)",
      "specific_Entity Fishing (%Entity Fishing)": "0 (0.00)",
      "relations with shared source+target (%Text2TCS ELG %Entity Fishing)": "0 (0.00 0.00)"
    },
    "Text2TCS ELG_vs_Spotlight": {
      "total_Text2TCS ELG": "10053",
      "total_Spotlight": "572",
      "common (%Text2TCS ELG %Spotlight)": "307 (0.03 0.54)",
      "common_partial_Text2TCS ELG_leq_Spotlight (%Spotlight)": "83 (0.15)",
      "common_partial_Spotlight_leq_Text2TCS ELG (%Text2TCS ELG)": "360 (0.04)",
      "specific_Text2TCS ELG (%Text2TCS ELG)": "9303 (0.93)",
      "specific_Spotlight (%Spotlight)": "0 (0.00)",
      "relations with shared source+target (%Text2TCS ELG %Spotlight)": "0 (0.00 0.00)"
    },
    "Text2TCS ELG_vs_NCBO Annotator": {
      "total_Text2TCS ELG": "10053",
      "total_NCBO Annotator": "31829",
      "common (%Text2TCS ELG %NCBO Annotator)": "6 (0.00 0.00)",
      "common_partial_Text2TCS ELG_leq_NCBO Annotator (%NCBO Annotator)": "0 (0.00)",
      "common_partial_NCBO Annotator_leq_Text2TCS ELG (%Text2TCS ELG)": "146 (0.01)",
      "specific_Text2TCS ELG (%Text2TCS ELG)": "9901 (0.98)",
      "specific_NCBO Annotator (%NCBO Annotator)": "31677 (1.00)"
    },
    "Text2TCS ELG_vs_USEA Annotator": {
      "total_Text2TCS ELG": "10053",
      "total_USEA Annotator": "31354",
      "common (%Text2TCS ELG %USEA Annotator)": "3077 (0.31 0.10)",
      "common_partial_Text2TCS ELG_leq_USEA Annotator (%USEA Annotator)": "865 (0.03)",
      "common_partial_USEA Annotator_leq_Text2TCS ELG (%Text2TCS ELG)": "1701 (0.17)",
      "specific_Text2TCS ELG (%Text2TCS ELG)": "4410 (0.44)",
      "specific_USEA Annotator (%USEA Annotator)": "25711 (0.82)"
    },
    "Entity Fishing_vs_Spotlight": {
      "total_Entity Fishing": "288",
      "total_Spotlight": "572",
      "common (%Entity Fishing %Spotlight)": "168 (0.58 0.29)",
      "common_partial_Entity Fishing_leq_Spotlight (%Spotlight)": "10 (0.02)",
      "common_partial_Spotlight_leq_Entity Fishing (%Entity Fishing)": "3 (0.01)",
      "specific_Entity Fishing (%Entity Fishing)": "107 (0.37)",
      "specific_Spotlight (%Spotlight)": "391 (0.68)",
      "relations with shared source+target (%Entity Fishing %Spotlight)": "13 (0.05 0.00)"
    },
    "Entity Fishing_vs_NCBO Annotator": {
      "total_Entity Fishing": "288",
      "total_NCBO Annotator": "31829",
      "common (%Entity Fishing %NCBO Annotator)": "0 (0.00 0.00)",
      "common_partial_Entity Fishing_leq_NCBO Annotator (%NCBO Annotator)": "0 (0.00)",
      "common_partial_NCBO Annotator_leq_Entity Fishing (%Entity Fishing)": "0 (0.00)",
      "specific_Entity Fishing (%Entity Fishing)": "288 (1.00)",
      "specific_NCBO Annotator (%NCBO Annotator)": "31829 (1.00)"
    },
    "Entity Fishing_vs_USEA Annotator": {
      "total_Entity Fishing": "288",
      "total_USEA Annotator": "31354",
      "common (%Entity Fishing %USEA Annotator)": "247 (0.86 0.01)",
      "common_partial_Entity Fishing_leq_USEA Annotator (%USEA Annotator)": "172 (0.01)",
      "common_partial_USEA Annotator_leq_Entity Fishing (%Entity Fishing)": "4 (0.01)",
      "specific_Entity Fishing (%Entity Fishing)": "0 (0.00)",
      "specific_USEA Annotator (%USEA Annotator)": "30931 (0.99)"
    },
    "Spotlight_vs_NCBO Annotator": {
      "total_Spotlight": "572",
      "total_NCBO Annotator": "31829",
      "common (%Spotlight %NCBO Annotator)": "0 (0.00 0.00)",
      "common_partial_Spotlight_leq_NCBO Annotator (%NCBO Annotator)": "0 (0.00)",
      "common_partial_NCBO Annotator_leq_Spotlight (%Spotlight)": "0 (0.00)",
      "specific_Spotlight (%Spotlight)": "572 (1.00)",
      "specific_NCBO Annotator (%NCBO Annotator)": "31829 (1.00)"
    },
    "Spotlight_vs_USEA Annotator": {
      "total_Spotlight": "572",
      "total_USEA Annotator": "31354",
      "common (%Spotlight %USEA Annotator)": "414 (0.72 0.01)",
      "common_partial_Spotlight_leq_USEA Annotator (%USEA Annotator)": "90 (0.00)",
      "common_partial_USEA Annotator_leq_Spotlight (%Spotlight)": "3 (0.01)",
      "specific_Spotlight (%Spotlight)": "65 (0.11)",
      "specific_USEA Annotator (%USEA Annotator)": "30847 (0.98)"
    },
    "NCBO Annotator_vs_USEA Annotator": {
      "total_NCBO Annotator": "31829",
      "total_USEA Annotator": "31354",
      "common (%NCBO Annotator %USEA Annotator)": "0 (0.00 0.00)",
      "common_partial_NCBO Annotator_leq_USEA Annotator (%USEA Annotator)": "0 (0.00)",
      "common_partial_USEA Annotator_leq_NCBO Annotator (%NCBO Annotator)": "0 (0.00)",
      "specific_NCBO Annotator (%NCBO Annotator)": "31829 (1.00)",
      "specific_USEA Annotator (%USEA Annotator)": "31354 (1.00)"
    }
  }
}```
