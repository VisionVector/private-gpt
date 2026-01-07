# Changelog

## [0.7.0](https://github.com/VisionVector/private-gpt/compare/v0.6.2...v0.7.0) (2026-01-07)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/VisionVector/private-gpt/issues/1426)) ([ce84e4c](https://github.com/VisionVector/private-gpt/commit/ce84e4c8c330f5c5e9b087fa35be9abebc2377cd))
* add retry connection to ollama ([#2084](https://github.com/VisionVector/private-gpt/issues/2084)) ([e82a09e](https://github.com/VisionVector/private-gpt/commit/e82a09eeed34165d0dc4720ad35232997c7248a5))
* Add stream information to generate SDKs ([#1569](https://github.com/VisionVector/private-gpt/issues/1569)) ([bc0938e](https://github.com/VisionVector/private-gpt/commit/bc0938e2c112ff11cb912447f1717e3ffec1cfc3))
* Adding MistralAI mode ([#2065](https://github.com/VisionVector/private-gpt/issues/2065)) ([b467e27](https://github.com/VisionVector/private-gpt/commit/b467e279071f3076aca1262df25e20a5abd38d84))
* **API:** Ingest plain text ([#1417](https://github.com/VisionVector/private-gpt/issues/1417)) ([5fb9eac](https://github.com/VisionVector/private-gpt/commit/5fb9eac9fa2174e4237b514ffeadc01559ca039c))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/VisionVector/private-gpt/issues/1432)) ([c48b6aa](https://github.com/VisionVector/private-gpt/commit/c48b6aa769018cbe45d1a194a1892041117a5d6b))
* bump dependencies ([#1987](https://github.com/VisionVector/private-gpt/issues/1987)) ([1d97ee2](https://github.com/VisionVector/private-gpt/commit/1d97ee26c89073b15aa6515483caf78b9eb88f2b))
* **code:** improve concat of strings in ui ([#1785](https://github.com/VisionVector/private-gpt/issues/1785)) ([b89d861](https://github.com/VisionVector/private-gpt/commit/b89d8612464e6bde2e72ad8bf318b3b063cddb0c))
* Disable Gradio Analytics ([#1165](https://github.com/VisionVector/private-gpt/issues/1165)) ([1fac365](https://github.com/VisionVector/private-gpt/commit/1fac365266cec8e06d7c7912292e2b7ad2b783a4))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/VisionVector/private-gpt/issues/1812)) ([ea508d6](https://github.com/VisionVector/private-gpt/commit/ea508d616553f6c82cd252b4d1da6d4b52cdc889))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/VisionVector/private-gpt/issues/1782)) ([43ae16e](https://github.com/VisionVector/private-gpt/commit/43ae16e6cba536f36ee1c94c091ea677acd0654a))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/VisionVector/private-gpt/issues/1924)) ([f68cb30](https://github.com/VisionVector/private-gpt/commit/f68cb3029444b1f69b9e3b66e8c39051bd7fc9d7))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/VisionVector/private-gpt/issues/1741)) ([64f20d2](https://github.com/VisionVector/private-gpt/commit/64f20d2bb0b14d6798fe8d25f7a8464081ddd231))
* **docs:** Fix setup docu ([#1926](https://github.com/VisionVector/private-gpt/issues/1926)) ([e06130f](https://github.com/VisionVector/private-gpt/commit/e06130fdca9e053908ffdb5af4eec3392deb7233))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/VisionVector/private-gpt/issues/1968)) ([63e88bf](https://github.com/VisionVector/private-gpt/commit/63e88bfcbaf647b3123e0ebfffec89e24ac856d3))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/VisionVector/private-gpt/issues/2000)) ([c620dc1](https://github.com/VisionVector/private-gpt/commit/c620dc10391bd44d666ebb8afbccd97282cb6ea3))
* **docs:** upgrade fern ([#1596](https://github.com/VisionVector/private-gpt/issues/1596)) ([7916e8e](https://github.com/VisionVector/private-gpt/commit/7916e8ee871399cb4ce84bd3cfcc78f926a80db4))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/VisionVector/private-gpt/issues/1133)) ([f7d7170](https://github.com/VisionVector/private-gpt/commit/f7d717023fa5dabcc1b7ec85fa3e645284f1fd10))
* enable resume download for hf_hub_download ([#1249](https://github.com/VisionVector/private-gpt/issues/1249)) ([3657117](https://github.com/VisionVector/private-gpt/commit/3657117b208a1732a02a438c42735f9f85a93c98))
* Get answers using preferred number of chunks ([d599256](https://github.com/VisionVector/private-gpt/commit/d599256d819fb41b727091bacbd1342989b89338))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/VisionVector/private-gpt/issues/1750)) ([5ac9d37](https://github.com/VisionVector/private-gpt/commit/5ac9d37c5ea01c16dbbaff25ac03020c58021326))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/VisionVector/private-gpt/issues/1698)) ([0d81cfc](https://github.com/VisionVector/private-gpt/commit/0d81cfc57562194f587d8fafe47c70a2a827c27d))
* **llm:** Add openailike llm mode ([#1447](https://github.com/VisionVector/private-gpt/issues/1447)) ([8f73b16](https://github.com/VisionVector/private-gpt/commit/8f73b16f598cf0e22a6ad73ca5eea5af42fc5033))
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/VisionVector/private-gpt/issues/2031)) ([0104d47](https://github.com/VisionVector/private-gpt/commit/0104d479e6fec30a0282a03b2650bcab89c7b7cd))
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/VisionVector/private-gpt/issues/1526)) ([9103816](https://github.com/VisionVector/private-gpt/commit/9103816cca8d078ab31875aa7377858a868e9d6c))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/VisionVector/private-gpt/issues/1703)) ([085ccdd](https://github.com/VisionVector/private-gpt/commit/085ccdd0e7a5957d5a6ed35c5c21a4888f84f278))
* **llm:** autopull ollama models ([#2019](https://github.com/VisionVector/private-gpt/issues/2019)) ([2f2ac95](https://github.com/VisionVector/private-gpt/commit/2f2ac957591f635f08950744c44f2eac00987cce))
* **llm:** drop default_system_prompt ([#1385](https://github.com/VisionVector/private-gpt/issues/1385)) ([075c3ed](https://github.com/VisionVector/private-gpt/commit/075c3ed2b6ebeb4a6b1367eb3572899a5d64ca5a))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/VisionVector/private-gpt/issues/1800)) ([297e0e0](https://github.com/VisionVector/private-gpt/commit/297e0e056ffd1d3df7545bee20188c617e49532c))
* **llm:** Ollama timeout setting ([#1773](https://github.com/VisionVector/private-gpt/issues/1773)) ([0aaf112](https://github.com/VisionVector/private-gpt/commit/0aaf11276b88f569436237f47f96b4dcea26965c))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/VisionVector/private-gpt/issues/1965)) ([374179a](https://github.com/VisionVector/private-gpt/commit/374179a358f2d254041cd54dea838533362b01ef))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/VisionVector/private-gpt/issues/1467)) ([1edccc5](https://github.com/VisionVector/private-gpt/commit/1edccc585a3e163a8d81c4891ff80639f19463ef))
* make llama3.1 as default ([#2022](https://github.com/VisionVector/private-gpt/issues/2022)) ([1019d4f](https://github.com/VisionVector/private-gpt/commit/1019d4f9861688a999cfb325e32df11d4a5b243b))
* move torch and transformers to local group ([#1172](https://github.com/VisionVector/private-gpt/issues/1172)) ([21baec7](https://github.com/VisionVector/private-gpt/commit/21baec7e905b33f732190f0e938fdc34985bac14))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/VisionVector/private-gpt/issues/1706)) ([1010b52](https://github.com/VisionVector/private-gpt/commit/1010b52b50b0aa09e797ae2af2f05a1c39f9b445))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/VisionVector/private-gpt/issues/1835)) ([7245f63](https://github.com/VisionVector/private-gpt/commit/7245f63c48612aa9b3ac4deb2c17f6104322f2b7))
* Qdrant support ([#1228](https://github.com/VisionVector/private-gpt/issues/1228)) ([8d7d002](https://github.com/VisionVector/private-gpt/commit/8d7d0022413e152873bd042eaafcfe876f5d517f))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/VisionVector/private-gpt/issues/1771)) ([eb8da20](https://github.com/VisionVector/private-gpt/commit/eb8da202c705e89258f1fc0b298a711efe84a34c))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/VisionVector/private-gpt/issues/1810)) ([5c027b5](https://github.com/VisionVector/private-gpt/commit/5c027b54b169717ebf599136498854b980072897))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/VisionVector/private-gpt/issues/2028)) ([1689b6d](https://github.com/VisionVector/private-gpt/commit/1689b6dde100d076204ba2c234f1e2bf378701e7))
* Release GitHub action ([#1078](https://github.com/VisionVector/private-gpt/issues/1078)) ([6a4318e](https://github.com/VisionVector/private-gpt/commit/6a4318e03c4eaead3c54146957d346b987e51ef9))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/VisionVector/private-gpt/issues/1783)) ([68d97f0](https://github.com/VisionVector/private-gpt/commit/68d97f090620a8dfddeba7c926d02b9b5d67f5c6))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/VisionVector/private-gpt/issues/1437)) ([4e028bf](https://github.com/VisionVector/private-gpt/commit/4e028bf08632b3d40f3eb154e116936ddd5a4100))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/VisionVector/private-gpt/issues/1415)) ([3e33799](https://github.com/VisionVector/private-gpt/commit/3e33799da7fc74f358cabecf9786d769a26f9b72))
* **ui:** add LLM mode to UI ([#1080](https://github.com/VisionVector/private-gpt/issues/1080)) ([3a59703](https://github.com/VisionVector/private-gpt/commit/3a5970322694ad083c711a4cb81ccf4c773b1d8a))
* **ui:** Add Model Information to ChatInterface label ([612c6b9](https://github.com/VisionVector/private-gpt/commit/612c6b96b29ce103148a52198b87f5152038305f))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/VisionVector/private-gpt/issues/1705)) ([d12c08e](https://github.com/VisionVector/private-gpt/commit/d12c08e03f34850958a063e8e726cbfc7965f6e7))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/VisionVector/private-gpt/issues/1353)) ([4194473](https://github.com/VisionVector/private-gpt/commit/4194473420e074d6d68b2c35c93b3635e739b25a))
* **UI:** Faster startup and document listing ([#1763](https://github.com/VisionVector/private-gpt/issues/1763)) ([52f2002](https://github.com/VisionVector/private-gpt/commit/52f20021f704ed8041da02cadaca6d2c2f301b26))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/VisionVector/private-gpt/issues/1643)) ([0e4d30f](https://github.com/VisionVector/private-gpt/commit/0e4d30f890e26c9a1a88835a54e2049dc12cce3d))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/VisionVector/private-gpt/issues/1397)) ([c2246ea](https://github.com/VisionVector/private-gpt/commit/c2246ea839905e68d46d16ed5cbce9837275b8b3))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/VisionVector/private-gpt/issues/1612)) ([d4b055e](https://github.com/VisionVector/private-gpt/commit/d4b055ebc3f6e4c5abf5c37b1e3b2d9e65eab26b))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/VisionVector/private-gpt/issues/1730)) ([633cc97](https://github.com/VisionVector/private-gpt/commit/633cc97ae9ef4afa8d1b66aa956016d0ac1d9b1c))
* update llama-index + dependencies ([#2092](https://github.com/VisionVector/private-gpt/issues/2092)) ([4d705c8](https://github.com/VisionVector/private-gpt/commit/4d705c88261b7e8ea317db06b7a9fffae36cdf93))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/VisionVector/private-gpt/issues/1663)) ([53d0d16](https://github.com/VisionVector/private-gpt/commit/53d0d164d189e31a34b17c800e59b8624c429773))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/VisionVector/private-gpt/issues/1996)) ([2255971](https://github.com/VisionVector/private-gpt/commit/22559711f08eacc8f9e465ef95917e092e5eb3c6))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/VisionVector/private-gpt/issues/1883)) ([462f898](https://github.com/VisionVector/private-gpt/commit/462f898cd89c2ee45fe91fa92c06fcd521b61b5c))
* **Vector:** support pgvector ([#1624](https://github.com/VisionVector/private-gpt/issues/1624)) ([17d74c6](https://github.com/VisionVector/private-gpt/commit/17d74c66ac21c302eeb3195b7a4e7ce557d985f9))
* wipe per storage type ([#1772](https://github.com/VisionVector/private-gpt/issues/1772)) ([df37b6a](https://github.com/VisionVector/private-gpt/commit/df37b6a07bbc3633b7603505f0bc424a55c4be6f))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/VisionVector/private-gpt/issues/1841)) ([6b31353](https://github.com/VisionVector/private-gpt/commit/6b31353b7360869f0aea4be1100a27c76415d7a9))
* 294 (tested) ([1f885ed](https://github.com/VisionVector/private-gpt/commit/1f885ed581b72db92a0ecaf231c731d72ecf299a))
* 503 when private gpt gets ollama service ([#2104](https://github.com/VisionVector/private-gpt/issues/2104)) ([bad326c](https://github.com/VisionVector/private-gpt/commit/bad326c85bebb73d4c8edd56c70a1b7519a8f6ec))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([c5aefeb](https://github.com/VisionVector/private-gpt/commit/c5aefeb39ed55ddf751a82c506a69a825bcb7e13))
* add built image from DockerHub ([#2042](https://github.com/VisionVector/private-gpt/issues/2042)) ([ec0ac19](https://github.com/VisionVector/private-gpt/commit/ec0ac19c32d0563dc6899d5309a61a06f51c2bdd))
* Add default mode option to settings ([#2078](https://github.com/VisionVector/private-gpt/issues/2078)) ([1cd047f](https://github.com/VisionVector/private-gpt/commit/1cd047fccc033f1fa9a21660493dc039f006db59))
* add numpy issue to troubleshooting ([#2048](https://github.com/VisionVector/private-gpt/issues/2048)) ([7279b49](https://github.com/VisionVector/private-gpt/commit/7279b4905c16c286bcb3caef014f2b965851b67d))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/VisionVector/private-gpt/issues/1519)) ([cc1e5ed](https://github.com/VisionVector/private-gpt/commit/cc1e5ed346062d6e7148503c23e1cb8364034546))
* Adding azopenai to model list ([#2035](https://github.com/VisionVector/private-gpt/issues/2035)) ([40095ae](https://github.com/VisionVector/private-gpt/commit/40095aec286f4fe7cc4316854385bf98b6fc2b58))
* auto-update version ([#2052](https://github.com/VisionVector/private-gpt/issues/2052)) ([1d6d161](https://github.com/VisionVector/private-gpt/commit/1d6d161963235015bbb7e7046c874e28297b7533))
* chromadb max batch size ([#1087](https://github.com/VisionVector/private-gpt/issues/1087)) ([ab8de72](https://github.com/VisionVector/private-gpt/commit/ab8de722a08a56ba850072db3975cbb37fc1af8e))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/VisionVector/private-gpt/issues/1998)) ([94ee861](https://github.com/VisionVector/private-gpt/commit/94ee86164e5afa5661144c1121e8347e75e55809))
* **deploy:** fix local and external dockerfiles ([94cbdfd](https://github.com/VisionVector/private-gpt/commit/94cbdfdaf8288bbcd715052915bf5eef748b5ea6))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/VisionVector/private-gpt/issues/2038)) ([d8401a2](https://github.com/VisionVector/private-gpt/commit/d8401a25f4bca91e57cb7298c12707ccd0089901))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/VisionVector/private-gpt/issues/2037)) ([3577f57](https://github.com/VisionVector/private-gpt/commit/3577f570ca2eb81885a50a35d22482885eea0c80))
* Disable Chroma Telemetry ([fcd0820](https://github.com/VisionVector/private-gpt/commit/fcd0820f8ccac29832a6b61dd6ac23ae90b32f9e))
* Docker and sagemaker setup ([#1118](https://github.com/VisionVector/private-gpt/issues/1118)) ([00cb94b](https://github.com/VisionVector/private-gpt/commit/00cb94b12326e1fd2d97887c5399cdacddacf9e5))
* docker permissions ([#2059](https://github.com/VisionVector/private-gpt/issues/2059)) ([abd2f17](https://github.com/VisionVector/private-gpt/commit/abd2f175952127bf2107c29824154e07f1307a94))
* **docker:** docker broken copy ([#1419](https://github.com/VisionVector/private-gpt/issues/1419)) ([ceb2259](https://github.com/VisionVector/private-gpt/commit/ceb225972e1843066549466eb35c65810a44cd12))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/VisionVector/private-gpt/issues/1779)) ([a9a8536](https://github.com/VisionVector/private-gpt/commit/a9a85365e19d6600fcf19c8b1f34cbf5f4053129))
* **docs:** Minor documentation amendment ([#1739](https://github.com/VisionVector/private-gpt/issues/1739)) ([db1ab3c](https://github.com/VisionVector/private-gpt/commit/db1ab3c2f1d1eea3b0f10703444a5ecf56118f13))
* **docs:** Update installation.mdx ([#1866](https://github.com/VisionVector/private-gpt/issues/1866)) ([8b77dfb](https://github.com/VisionVector/private-gpt/commit/8b77dfb742ac175ca2318635881433712efcd424))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([fc2e58d](https://github.com/VisionVector/private-gpt/commit/fc2e58d6ce5d9b784dc72ce9a756e7be731a0f2b))
* ffmpy dependency ([#2020](https://github.com/VisionVector/private-gpt/issues/2020)) ([2e38ebb](https://github.com/VisionVector/private-gpt/commit/2e38ebbc9bf139101d35f2dc7bf170dcc64ef77b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/VisionVector/private-gpt/issues/1123)) ([e18d97f](https://github.com/VisionVector/private-gpt/commit/e18d97f32b6db048500bfe6edd715f666092d0d1))
* Fixed docker-compose ([#1758](https://github.com/VisionVector/private-gpt/issues/1758)) ([0d26c1a](https://github.com/VisionVector/private-gpt/commit/0d26c1ad9897540679e77fbb770e5a8d64bffb11))
* **ingest:** update script label ([#1770](https://github.com/VisionVector/private-gpt/issues/1770)) ([11dfcab](https://github.com/VisionVector/private-gpt/commit/11dfcabae11a000b78ef4f04b52c833846ef1b1a))
* light mode ([#2025](https://github.com/VisionVector/private-gpt/issues/2025)) ([d2a914d](https://github.com/VisionVector/private-gpt/commit/d2a914d9f56b73c1a59edc5c3f1c4fa3259ccde0))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/VisionVector/private-gpt/issues/1954)) ([da479be](https://github.com/VisionVector/private-gpt/commit/da479bef193e8d2545f0c2ca5302f1fa939fcfcd))
* **llm:** special tokens and leading space ([#1831](https://github.com/VisionVector/private-gpt/issues/1831)) ([962492b](https://github.com/VisionVector/private-gpt/commit/962492bc8dd83fa7fe6e946d251b7c03117425ef))
* make docs more visible ([#1081](https://github.com/VisionVector/private-gpt/issues/1081)) ([29c06fd](https://github.com/VisionVector/private-gpt/commit/29c06fdcf44d5d3457e906dcc4b007c501d21d1a))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/VisionVector/private-gpt/issues/1859)) ([cfaca4d](https://github.com/VisionVector/private-gpt/commit/cfaca4d68fa986263c1a6a7263685e8f114fed54))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/VisionVector/private-gpt/issues/1449)) ([d471b8c](https://github.com/VisionVector/private-gpt/commit/d471b8c5ff9622dcbe62bbe3b39fb48e92d68246))
* naming image and ollama-cpu ([#2056](https://github.com/VisionVector/private-gpt/issues/2056)) ([8d8d728](https://github.com/VisionVector/private-gpt/commit/8d8d7285ef1448c591696bb172d79e7b7a09c993))
* nomic embeddings ([#2030](https://github.com/VisionVector/private-gpt/issues/2030)) ([1b84d4c](https://github.com/VisionVector/private-gpt/commit/1b84d4cd23bf491995da8bb1abbac2ae0f5f3f75))
* prevent to ingest local files (by default) ([#2010](https://github.com/VisionVector/private-gpt/issues/2010)) ([f7519e2](https://github.com/VisionVector/private-gpt/commit/f7519e2c0689587250d1276baf330ff6b31d151c))
* publish image name ([#2043](https://github.com/VisionVector/private-gpt/issues/2043)) ([ae17b58](https://github.com/VisionVector/private-gpt/commit/ae17b58cc676db607e377b6e4c73ebfd9cf5e522))
* Rectify ffmpy poetry config; update version from 0.3.2 to 0.4.0 ([#2062](https://github.com/VisionVector/private-gpt/issues/2062)) ([20872d8](https://github.com/VisionVector/private-gpt/commit/20872d8a2c9387292e82e3c592eb39953f588e63))
* Remove global state ([#1216](https://github.com/VisionVector/private-gpt/issues/1216)) ([c003889](https://github.com/VisionVector/private-gpt/commit/c003889f318fb0b13246ac165f6c3cb3928ff1aa))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/VisionVector/private-gpt/issues/1890)) ([5f2ca1c](https://github.com/VisionVector/private-gpt/commit/5f2ca1cb5e78dcf6ada74ee6a3af558f5014fc39))
* sagemaker config and chat methods ([#1142](https://github.com/VisionVector/private-gpt/issues/1142)) ([f03cb58](https://github.com/VisionVector/private-gpt/commit/f03cb58ee559bf6dabeb33c2e62586faeb8b3311))
* Sanitize null bytes before ingestion ([#2090](https://github.com/VisionVector/private-gpt/issues/2090)) ([845060a](https://github.com/VisionVector/private-gpt/commit/845060af957cb7f765578307fbf8017e252ede21))
* **settings:** correct yaml multiline string ([#1403](https://github.com/VisionVector/private-gpt/issues/1403)) ([6f1cbe4](https://github.com/VisionVector/private-gpt/commit/6f1cbe46438f26f24a795f0b32d41229a6bc4931))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/VisionVector/private-gpt/issues/1925)) ([0de0704](https://github.com/VisionVector/private-gpt/commit/0de0704184109737903f860c42c8af38154c3454))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/VisionVector/private-gpt/issues/1709)) ([fc9e5d2](https://github.com/VisionVector/private-gpt/commit/fc9e5d29fe2d41db33b713c47781649a5353f139))
* **tests:** load the test settings only when running tests ([4e6aa00](https://github.com/VisionVector/private-gpt/commit/4e6aa00a413f97f03f2bacf03d9238009e8763ea))
* typo in README.md ([#1091](https://github.com/VisionVector/private-gpt/issues/1091)) ([9405690](https://github.com/VisionVector/private-gpt/commit/94056904d96673566e4c15f5a8259d13ff12e961))
* **ui:** gradio bug fixes ([#2021](https://github.com/VisionVector/private-gpt/issues/2021)) ([0d3c38b](https://github.com/VisionVector/private-gpt/commit/0d3c38bdfd73939b80eb4272d0a209fb82426782))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([3418c33](https://github.com/VisionVector/private-gpt/commit/3418c33a23b9b398a119ae5174927a9ddc43ba92))
* unify embedding models ([#2027](https://github.com/VisionVector/private-gpt/issues/2027)) ([fa63aa9](https://github.com/VisionVector/private-gpt/commit/fa63aa9075180958f4d72a1b97598b9145833d77))
* update matplotlib to 3.9.1-post1 to fix win install ([a8f1b80](https://github.com/VisionVector/private-gpt/commit/a8f1b80db836d5876697c534bedce634e40b7530))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/VisionVector/private-gpt/issues/1260)) ([4bd3395](https://github.com/VisionVector/private-gpt/commit/4bd33957e4323c603024431f6233b46c67c4f942))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/VisionVector/private-gpt/issues/1280)) ([e9bbbd0](https://github.com/VisionVector/private-gpt/commit/e9bbbd062b29da8959aaadb313318cabaa24f6c3))

## [0.6.2](https://github.com/zylon-ai/private-gpt/compare/v0.6.1...v0.6.2) (2024-08-08)


### Bug Fixes

* add numpy issue to troubleshooting ([#2048](https://github.com/zylon-ai/private-gpt/issues/2048)) ([4ca6d0c](https://github.com/zylon-ai/private-gpt/commit/4ca6d0cb556be7a598f7d3e3b00d2a29214ee1e8))
* auto-update version ([#2052](https://github.com/zylon-ai/private-gpt/issues/2052)) ([7fefe40](https://github.com/zylon-ai/private-gpt/commit/7fefe408b4267684c6e3c1a43c5dc2b73ec61fe4))
* publish image name ([#2043](https://github.com/zylon-ai/private-gpt/issues/2043)) ([b1acf9d](https://github.com/zylon-ai/private-gpt/commit/b1acf9dc2cbca2047cd0087f13254ff5cda6e570))
* update matplotlib to 3.9.1-post1 to fix win install ([b16abbe](https://github.com/zylon-ai/private-gpt/commit/b16abbefe49527ac038d235659854b98345d5387))

## [0.6.1](https://github.com/zylon-ai/private-gpt/compare/v0.6.0...v0.6.1) (2024-08-05)


### Bug Fixes

* add built image from DockerHub ([#2042](https://github.com/zylon-ai/private-gpt/issues/2042)) ([f09f6dd](https://github.com/zylon-ai/private-gpt/commit/f09f6dd2553077d4566dbe6b48a450e05c2f049e))
* Adding azopenai to model list ([#2035](https://github.com/zylon-ai/private-gpt/issues/2035)) ([1c665f7](https://github.com/zylon-ai/private-gpt/commit/1c665f7900658144f62814b51f6e3434a6d7377f))
* **deploy:** generate docker release when new version is released ([#2038](https://github.com/zylon-ai/private-gpt/issues/2038)) ([1d4c14d](https://github.com/zylon-ai/private-gpt/commit/1d4c14d7a3c383c874b323d934be01afbaca899e))
* **deploy:** improve Docker-Compose and quickstart on Docker ([#2037](https://github.com/zylon-ai/private-gpt/issues/2037)) ([dae0727](https://github.com/zylon-ai/private-gpt/commit/dae0727a1b4abd35d2b0851fe30e0a4ed67e0fbb))

## [0.6.0](https://github.com/zylon-ai/private-gpt/compare/v0.5.0...v0.6.0) (2024-08-02)


### Features

* bump dependencies ([#1987](https://github.com/zylon-ai/private-gpt/issues/1987)) ([b687dc8](https://github.com/zylon-ai/private-gpt/commit/b687dc852413404c52d26dcb94536351a63b169d))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/zylon-ai/private-gpt/issues/1924)) ([d13029a](https://github.com/zylon-ai/private-gpt/commit/d13029a046f6e19e8ee65bef3acd96365c738df2))
* **docs:** Fix setup docu ([#1926](https://github.com/zylon-ai/private-gpt/issues/1926)) ([067a5f1](https://github.com/zylon-ai/private-gpt/commit/067a5f144ca6e605c99d7dbe9ca7d8207ac8808d))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/zylon-ai/private-gpt/issues/1968)) ([19a7c06](https://github.com/zylon-ai/private-gpt/commit/19a7c065ef7f42b37f289dd28ac945f7afc0e73a))
* **docs:** update documentation and fix preview-docs ([#2000](https://github.com/zylon-ai/private-gpt/issues/2000)) ([4523a30](https://github.com/zylon-ai/private-gpt/commit/4523a30c8f004aac7a7ae224671e2c45ec0cb973))
* **llm:** add progress bar when ollama is pulling models ([#2031](https://github.com/zylon-ai/private-gpt/issues/2031)) ([cf61bf7](https://github.com/zylon-ai/private-gpt/commit/cf61bf780f8d122e4057d002abf03563bb45614a))
* **llm:** autopull ollama models ([#2019](https://github.com/zylon-ai/private-gpt/issues/2019)) ([20bad17](https://github.com/zylon-ai/private-gpt/commit/20bad17c9857809158e689e9671402136c1e3d84))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/zylon-ai/private-gpt/issues/1965)) ([fc13368](https://github.com/zylon-ai/private-gpt/commit/fc13368bc72d1f4c27644677431420ed77731c03))
* make llama3.1 as default ([#2022](https://github.com/zylon-ai/private-gpt/issues/2022)) ([9027d69](https://github.com/zylon-ai/private-gpt/commit/9027d695c11fbb01e62424b855665de71d513417))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/zylon-ai/private-gpt/issues/1835)) ([e21bf20](https://github.com/zylon-ai/private-gpt/commit/e21bf20c10938b24711d9f2c765997f44d7e02a9))
* **recipe:** add our first recipe  `Summarize` ([#2028](https://github.com/zylon-ai/private-gpt/issues/2028)) ([8119842](https://github.com/zylon-ai/private-gpt/commit/8119842ae6f1f5ecfaf42b06fa0d1ffec675def4))
* **vectordb:** Milvus vector db Integration ([#1996](https://github.com/zylon-ai/private-gpt/issues/1996)) ([43cc31f](https://github.com/zylon-ai/private-gpt/commit/43cc31f74015f8d8fcbf7a8ea7d7d9ecc66cf8c9))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/zylon-ai/private-gpt/issues/1883)) ([2612928](https://github.com/zylon-ai/private-gpt/commit/26129288394c7483e6fc0496a11dc35679528cc1))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/zylon-ai/private-gpt/issues/1841)) ([947e737](https://github.com/zylon-ai/private-gpt/commit/947e737f300adf621d2261d527192f36f3387f8e))
* **config:** make tokenizer optional and include a troubleshooting doc ([#1998](https://github.com/zylon-ai/private-gpt/issues/1998)) ([01b7ccd](https://github.com/zylon-ai/private-gpt/commit/01b7ccd0648be032846647c9a184925d3682f612))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/zylon-ai/private-gpt/issues/1779)) ([dde0224](https://github.com/zylon-ai/private-gpt/commit/dde02245bcd51a7ede7b6789c82ae217cac53d92))
* **docs:** Update installation.mdx ([#1866](https://github.com/zylon-ai/private-gpt/issues/1866)) ([c1802e7](https://github.com/zylon-ai/private-gpt/commit/c1802e7cf0e56a2603213ec3b6a4af8fadb8a17a))
* ffmpy dependency ([#2020](https://github.com/zylon-ai/private-gpt/issues/2020)) ([dabf556](https://github.com/zylon-ai/private-gpt/commit/dabf556dae9cb00fe0262270e5138d982585682e))
* light mode ([#2025](https://github.com/zylon-ai/private-gpt/issues/2025)) ([1020cd5](https://github.com/zylon-ai/private-gpt/commit/1020cd53288af71a17882781f392512568f1b846))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/zylon-ai/private-gpt/issues/1954)) ([c7212ac](https://github.com/zylon-ai/private-gpt/commit/c7212ac7cc891f9e3c713cc206ae9807c5dfdeb6))
* **llm:** special tokens and leading space ([#1831](https://github.com/zylon-ai/private-gpt/issues/1831)) ([347be64](https://github.com/zylon-ai/private-gpt/commit/347be643f7929c56382a77c3f45f0867605e0e0a))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/zylon-ai/private-gpt/issues/1859)) ([2a432bf](https://github.com/zylon-ai/private-gpt/commit/2a432bf9c5582a94eb4052b1e80cabdb118d298e))
* nomic embeddings ([#2030](https://github.com/zylon-ai/private-gpt/issues/2030)) ([5465958](https://github.com/zylon-ai/private-gpt/commit/54659588b5b109a3dd17cca835e275240464d275))
* prevent to ingest local files (by default) ([#2010](https://github.com/zylon-ai/private-gpt/issues/2010)) ([e54a8fe](https://github.com/zylon-ai/private-gpt/commit/e54a8fe0433252808d0a60f6a08a43c9f5a42f3b))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/zylon-ai/private-gpt/issues/1890)) ([9d0d614](https://github.com/zylon-ai/private-gpt/commit/9d0d614706581a8bfa57db45f62f84ab23d26f15))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/zylon-ai/private-gpt/issues/1925)) ([966af47](https://github.com/zylon-ai/private-gpt/commit/966af4771dbe5cf3fdf554b5fdf8f732407859c4))
* **ui:** gradio bug fixes ([#2021](https://github.com/zylon-ai/private-gpt/issues/2021)) ([d4375d0](https://github.com/zylon-ai/private-gpt/commit/d4375d078f18ba53562fd71651159f997fff865f))
* unify embedding models ([#2027](https://github.com/zylon-ai/private-gpt/issues/2027)) ([40638a1](https://github.com/zylon-ai/private-gpt/commit/40638a18a5713d60fec8fe52796dcce66d88258c))

## [0.5.0](https://github.com/zylon-ai/private-gpt/compare/v0.4.0...v0.5.0) (2024-04-02)


### Features

* **code:** improve concat of strings in ui ([#1785](https://github.com/zylon-ai/private-gpt/issues/1785)) ([bac818a](https://github.com/zylon-ai/private-gpt/commit/bac818add51b104cda925b8f1f7b51448e935ca1))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/zylon-ai/private-gpt/issues/1812)) ([f83abff](https://github.com/zylon-ai/private-gpt/commit/f83abff8bc955a6952c92cc7bcb8985fcec93afa))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/zylon-ai/private-gpt/issues/1782)) ([8a836e4](https://github.com/zylon-ai/private-gpt/commit/8a836e4651543f099c59e2bf497ab8c55a7cd2e5))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/zylon-ai/private-gpt/issues/1741)) ([5725181](https://github.com/zylon-ai/private-gpt/commit/572518143ac46532382db70bed6f73b5082302c1))
* **docs:** upgrade fern ([#1596](https://github.com/zylon-ai/private-gpt/issues/1596)) ([84ad16a](https://github.com/zylon-ai/private-gpt/commit/84ad16af80191597a953248ce66e963180e8ddec))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/zylon-ai/private-gpt/issues/1750)) ([134fc54](https://github.com/zylon-ai/private-gpt/commit/134fc54d7d636be91680dc531f5cbe2c5892ac56))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/zylon-ai/private-gpt/issues/1698)) ([1efac6a](https://github.com/zylon-ai/private-gpt/commit/1efac6a3fe19e4d62325e2c2915cd84ea277f04f))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/zylon-ai/private-gpt/issues/1703)) ([02dc83e](https://github.com/zylon-ai/private-gpt/commit/02dc83e8e9f7ada181ff813f25051bbdff7b7c6b))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/zylon-ai/private-gpt/issues/1800)) ([b3b0140](https://github.com/zylon-ai/private-gpt/commit/b3b0140e244e7a313bfaf4ef10eb0f7e4192710e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/zylon-ai/private-gpt/issues/1773)) ([6f6c785](https://github.com/zylon-ai/private-gpt/commit/6f6c785dac2bbad37d0b67fda215784298514d39))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/zylon-ai/private-gpt/issues/1467)) ([821bca3](https://github.com/zylon-ai/private-gpt/commit/821bca32e9ee7c909fd6488445ff6a04463bf91b))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/zylon-ai/private-gpt/issues/1706)) ([68b3a34](https://github.com/zylon-ai/private-gpt/commit/68b3a34b032a08ca073a687d2058f926032495b3))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/zylon-ai/private-gpt/issues/1771)) ([087cb0b](https://github.com/zylon-ai/private-gpt/commit/087cb0b7b74c3eb80f4f60b47b3a021c81272ae1))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/zylon-ai/private-gpt/issues/1810)) ([83adc12](https://github.com/zylon-ai/private-gpt/commit/83adc12a8ef0fa0c13a0dec084fa596445fc9075))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/zylon-ai/private-gpt/issues/1783)) ([ea153fb](https://github.com/zylon-ai/private-gpt/commit/ea153fb92f1f61f64c0d04fff0048d4d00b6f8d0))
* **ui:** Add Model Information to ChatInterface label ([f0b174c](https://github.com/zylon-ai/private-gpt/commit/f0b174c097c2d5e52deae8ef88de30a0d9013a38))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/zylon-ai/private-gpt/issues/1705)) ([290b9fb](https://github.com/zylon-ai/private-gpt/commit/290b9fb084632216300e89bdadbfeb0380724b12))
* **UI:** Faster startup and document listing ([#1763](https://github.com/zylon-ai/private-gpt/issues/1763)) ([348df78](https://github.com/zylon-ai/private-gpt/commit/348df781b51606b2f9810bcd46f850e54192fd16))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/zylon-ai/private-gpt/issues/1643)) ([410bf7a](https://github.com/zylon-ai/private-gpt/commit/410bf7a71f17e77c4aec723ab80c233b53765964))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/zylon-ai/private-gpt/issues/1730)) ([63de7e4](https://github.com/zylon-ai/private-gpt/commit/63de7e4930ac90dd87620225112a22ffcbbb31ee))
* wipe per storage type ([#1772](https://github.com/zylon-ai/private-gpt/issues/1772)) ([c2d6948](https://github.com/zylon-ai/private-gpt/commit/c2d694852b4696834962a42fde047b728722ad74))


### Bug Fixes

* **docs:** Minor documentation amendment ([#1739](https://github.com/zylon-ai/private-gpt/issues/1739)) ([258d02d](https://github.com/zylon-ai/private-gpt/commit/258d02d87c5cb81d6c3a6f06aa69339b670dffa9))
* Fixed docker-compose ([#1758](https://github.com/zylon-ai/private-gpt/issues/1758)) ([774e256](https://github.com/zylon-ai/private-gpt/commit/774e2560520dc31146561d09a2eb464c68593871))
* **ingest:** update script label ([#1770](https://github.com/zylon-ai/private-gpt/issues/1770)) ([7d2de5c](https://github.com/zylon-ai/private-gpt/commit/7d2de5c96fd42e339b26269b3155791311ef1d08))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/zylon-ai/private-gpt/issues/1709)) ([d17c34e](https://github.com/zylon-ai/private-gpt/commit/d17c34e81a84518086b93605b15032e2482377f7))

## [0.4.0](https://github.com/imartinez/privateGPT/compare/v0.3.0...v0.4.0) (2024-03-06)


### Features

* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/imartinez/privateGPT/issues/1663)) ([45f0571](https://github.com/imartinez/privateGPT/commit/45f05711eb71ffccdedb26f37e680ced55795d44))
* **Vector:** support pgvector ([#1624](https://github.com/imartinez/privateGPT/issues/1624)) ([cd40e39](https://github.com/imartinez/privateGPT/commit/cd40e3982b780b548b9eea6438c759f1c22743a8))

## [0.3.0](https://github.com/imartinez/privateGPT/compare/v0.2.0...v0.3.0) (2024-02-16)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/imartinez/privateGPT/issues/1426)) ([e326126](https://github.com/imartinez/privateGPT/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* Add stream information to generate SDKs ([#1569](https://github.com/imartinez/privateGPT/issues/1569)) ([24fae66](https://github.com/imartinez/privateGPT/commit/24fae660e6913aac6b52745fb2c2fe128ba2eb79))
* **API:** Ingest plain text ([#1417](https://github.com/imartinez/privateGPT/issues/1417)) ([6eeb95e](https://github.com/imartinez/privateGPT/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/imartinez/privateGPT/issues/1432)) ([b178b51](https://github.com/imartinez/privateGPT/commit/b178b514519550e355baf0f4f3f6beb73dca7df2))
* **llm:** Add openailike llm mode ([#1447](https://github.com/imartinez/privateGPT/issues/1447)) ([2d27a9f](https://github.com/imartinez/privateGPT/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/imartinez/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/imartinez/privateGPT/issues/1526)) ([6bbec79](https://github.com/imartinez/privateGPT/commit/6bbec79583b7f28d9bea4b39c099ebef149db843))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/imartinez/privateGPT/issues/1437)) ([4780540](https://github.com/imartinez/privateGPT/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/imartinez/privateGPT/issues/1415)) ([8ec7cf4](https://github.com/imartinez/privateGPT/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/imartinez/privateGPT/issues/1397)) ([c71ae7c](https://github.com/imartinez/privateGPT/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/imartinez/privateGPT/issues/1612)) ([aa13afd](https://github.com/imartinez/privateGPT/commit/aa13afde07122f2ddda3942f630e5cadc7e4e1ee))


### Bug Fixes

* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/imartinez/privateGPT/issues/1519)) ([869233f](https://github.com/imartinez/privateGPT/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/imartinez/privateGPT/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* **docker:** docker broken copy ([#1419](https://github.com/imartinez/privateGPT/issues/1419)) ([059f358](https://github.com/imartinez/privateGPT/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/imartinez/privateGPT/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/imartinez/privateGPT/issues/1449)) ([6191bcd](https://github.com/imartinez/privateGPT/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* **settings:** correct yaml multiline string ([#1403](https://github.com/imartinez/privateGPT/issues/1403)) ([2564f8d](https://github.com/imartinez/privateGPT/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/imartinez/privateGPT/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([24fb80c](https://github.com/imartinez/privateGPT/commit/24fb80ca38f21910fe4fd81505d14960e9ed4faa))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
