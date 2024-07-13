# Changelog

## 0.0.1 (2024-07-13)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/phantomwork/privateGPT/issues/1426)) ([c30fcd8](https://github.com/phantomwork/privateGPT/commit/c30fcd8eda3e92376f6b4b7a91ef6506460584c6))
* Add stream information to generate SDKs ([#1569](https://github.com/phantomwork/privateGPT/issues/1569)) ([5e92d75](https://github.com/phantomwork/privateGPT/commit/5e92d754d989705ccaeb547639be4a0a9f44db84))
* **API:** Ingest plain text ([#1417](https://github.com/phantomwork/privateGPT/issues/1417)) ([a8d84d4](https://github.com/phantomwork/privateGPT/commit/a8d84d4ded4d4d50eddc978dd1cd0dd95bd88ce7))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/phantomwork/privateGPT/issues/1432)) ([18fd69b](https://github.com/phantomwork/privateGPT/commit/18fd69bf8d0a48db53d816381cf5f7ce940912cb))
* bump dependencies ([#1987](https://github.com/phantomwork/privateGPT/issues/1987)) ([f918fae](https://github.com/phantomwork/privateGPT/commit/f918fae9777c6e474860f1ed9d4a3f5838ac2a7f))
* **code:** improve concat of strings in ui ([#1785](https://github.com/phantomwork/privateGPT/issues/1785)) ([e14b913](https://github.com/phantomwork/privateGPT/commit/e14b913d80f9324f099c13b85b92f55771fec880))
* Disable Gradio Analytics ([#1165](https://github.com/phantomwork/privateGPT/issues/1165)) ([2a0ea0e](https://github.com/phantomwork/privateGPT/commit/2a0ea0ed4f5a433295094e2094f81802cb16c2c3))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/phantomwork/privateGPT/issues/1812)) ([aa8aada](https://github.com/phantomwork/privateGPT/commit/aa8aadaa8ddb6351aa3fba0246faef8a35457d4b))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/phantomwork/privateGPT/issues/1782)) ([73f0c1a](https://github.com/phantomwork/privateGPT/commit/73f0c1a66e5413ad4d8c2663bb5898d7249c773a))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/phantomwork/privateGPT/issues/1924)) ([12720a3](https://github.com/phantomwork/privateGPT/commit/12720a387d575c5ff50079f2589585b12c0c3d18))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/phantomwork/privateGPT/issues/1741)) ([87d69a9](https://github.com/phantomwork/privateGPT/commit/87d69a92d91dfb558a04ed0d92fec8bcc0a82a21))
* **docs:** Fix setup docu ([#1926](https://github.com/phantomwork/privateGPT/issues/1926)) ([086f60c](https://github.com/phantomwork/privateGPT/commit/086f60c585645e456f54cf82e3f355de61557ffb))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/phantomwork/privateGPT/issues/1968)) ([84bc274](https://github.com/phantomwork/privateGPT/commit/84bc274d5cf2076c7a3fd674bc8608382a70cfdf))
* **docs:** upgrade fern ([#1596](https://github.com/phantomwork/privateGPT/issues/1596)) ([0e12cc5](https://github.com/phantomwork/privateGPT/commit/0e12cc59bf6ce9b7fc52d5b6d898c37237919a96))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/phantomwork/privateGPT/issues/1133)) ([10345ea](https://github.com/phantomwork/privateGPT/commit/10345eaa7a80bb5b567f7fc2165cea29e6ec125c))
* enable resume download for hf_hub_download ([#1249](https://github.com/phantomwork/privateGPT/issues/1249)) ([44f6d0b](https://github.com/phantomwork/privateGPT/commit/44f6d0bad6bf23fb198f52a3abab73b95e81ed67))
* Get answers using preferred number of chunks ([48492f4](https://github.com/phantomwork/privateGPT/commit/48492f49e1762e1d2758960687d1f6c63f822b3e))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/phantomwork/privateGPT/issues/1750)) ([2e0e980](https://github.com/phantomwork/privateGPT/commit/2e0e980f876ad396922e56b5a29378f7302850ef))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/phantomwork/privateGPT/issues/1698)) ([a2580d9](https://github.com/phantomwork/privateGPT/commit/a2580d98cd0c33f519b569d3a53b061b1cbf2b7d))
* **llm:** Add openailike llm mode ([#1447](https://github.com/phantomwork/privateGPT/issues/1447)) ([01d31c9](https://github.com/phantomwork/privateGPT/commit/01d31c9d6e3e56e874b124c25cf9c69930fe25e6)), closes [#1424](https://github.com/phantomwork/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/phantomwork/privateGPT/issues/1526)) ([5565a0f](https://github.com/phantomwork/privateGPT/commit/5565a0f70998b5294f894b58cccb3c33a0d7650c))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/phantomwork/privateGPT/issues/1703)) ([ed0f207](https://github.com/phantomwork/privateGPT/commit/ed0f2073033600f24f6c58b94598cddba6287824))
* **llm:** drop default_system_prompt ([#1385](https://github.com/phantomwork/privateGPT/issues/1385)) ([aeed96f](https://github.com/phantomwork/privateGPT/commit/aeed96f563edc07779df42e3e305a4f32d816b52))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/phantomwork/privateGPT/issues/1800)) ([0145a1f](https://github.com/phantomwork/privateGPT/commit/0145a1f507611d01bd27da35c26a93380470e91c))
* **llm:** Ollama timeout setting ([#1773](https://github.com/phantomwork/privateGPT/issues/1773)) ([cfe6fc9](https://github.com/phantomwork/privateGPT/commit/cfe6fc94709d88e66b30c0c9ea53df2afd7c74b8))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/phantomwork/privateGPT/issues/1965)) ([0027ee8](https://github.com/phantomwork/privateGPT/commit/0027ee8f812711479befb1bde931d7f2da8e3487))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/phantomwork/privateGPT/issues/1467)) ([b07841d](https://github.com/phantomwork/privateGPT/commit/b07841de5754cbb7a557dd28cf9aa815c874cf29))
* move torch and transformers to local group ([#1172](https://github.com/phantomwork/privateGPT/issues/1172)) ([35b7214](https://github.com/phantomwork/privateGPT/commit/35b7214360150b3d65149a1f36a3ed93530ed0df))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/phantomwork/privateGPT/issues/1706)) ([8385b93](https://github.com/phantomwork/privateGPT/commit/8385b9396387c1de6863037ac245b29652763053))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/phantomwork/privateGPT/issues/1835)) ([b7807e0](https://github.com/phantomwork/privateGPT/commit/b7807e0adaaab910242b2f8d5821ad0968b8ecb1))
* Qdrant support ([#1228](https://github.com/phantomwork/privateGPT/issues/1228)) ([3d316d6](https://github.com/phantomwork/privateGPT/commit/3d316d688b6da4f4609060695f9321edb1ec23de))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/phantomwork/privateGPT/issues/1771)) ([a96018f](https://github.com/phantomwork/privateGPT/commit/a96018ffcee3b11a15439e29e036c2daefeafbd0))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/phantomwork/privateGPT/issues/1810)) ([476c3bb](https://github.com/phantomwork/privateGPT/commit/476c3bb41c72dbf2020ee685b624ff1d5a30b397))
* Release GitHub action ([#1078](https://github.com/phantomwork/privateGPT/issues/1078)) ([8fdd2a3](https://github.com/phantomwork/privateGPT/commit/8fdd2a31e9f97cfd5b1415e704925be11f6e0d79))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/phantomwork/privateGPT/issues/1783)) ([390696b](https://github.com/phantomwork/privateGPT/commit/390696b4df62d8a50c93ef09c3f21eb4d982d050))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/phantomwork/privateGPT/issues/1437)) ([3a602d7](https://github.com/phantomwork/privateGPT/commit/3a602d7b657c6bc962ffd250d5dfd3ef3fc4c96b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/phantomwork/privateGPT/issues/1415)) ([c1431c4](https://github.com/phantomwork/privateGPT/commit/c1431c4d88132b34530c26873b2f916f37fb3225))
* **ui:** add LLM mode to UI ([#1080](https://github.com/phantomwork/privateGPT/issues/1080)) ([04d6983](https://github.com/phantomwork/privateGPT/commit/04d69832c407444a60310a4878bf6b9151da6f84))
* **ui:** Add Model Information to ChatInterface label ([dfff863](https://github.com/phantomwork/privateGPT/commit/dfff86352c17b7868d0aacdd957d50b0f8a819f9))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/phantomwork/privateGPT/issues/1705)) ([059274a](https://github.com/phantomwork/privateGPT/commit/059274a87e457775a3927fc5652842153c07a3f1))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/phantomwork/privateGPT/issues/1353)) ([684bdc8](https://github.com/phantomwork/privateGPT/commit/684bdc84e211c7785897da86a4e228655a7503a9))
* **UI:** Faster startup and document listing ([#1763](https://github.com/phantomwork/privateGPT/issues/1763)) ([914f231](https://github.com/phantomwork/privateGPT/commit/914f231e8a974a7ab7c51c35d21cd705dc84756c))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/phantomwork/privateGPT/issues/1643)) ([34a209f](https://github.com/phantomwork/privateGPT/commit/34a209f6af391cf85158cef878e47225406a0cf8))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/phantomwork/privateGPT/issues/1397)) ([9afddc0](https://github.com/phantomwork/privateGPT/commit/9afddc01486b48404087bf654a77e634ffd59cfa))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/phantomwork/privateGPT/issues/1612)) ([f4d011a](https://github.com/phantomwork/privateGPT/commit/f4d011a66260fed00a22c7ac663de3b43ad34ace))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/phantomwork/privateGPT/issues/1730)) ([e9af24a](https://github.com/phantomwork/privateGPT/commit/e9af24a50ec39fa080063e650d0b8c39be51ff26))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/phantomwork/privateGPT/issues/1663)) ([4671a92](https://github.com/phantomwork/privateGPT/commit/4671a924d0f6c2498b6be8dc70194ae5d892e791))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/phantomwork/privateGPT/issues/1883)) ([7213d3b](https://github.com/phantomwork/privateGPT/commit/7213d3b6face5f3a9e36c05d40af94fb75e63573))
* **Vector:** support pgvector ([#1624](https://github.com/phantomwork/privateGPT/issues/1624)) ([dc24ab2](https://github.com/phantomwork/privateGPT/commit/dc24ab2593953eb30b2caf20cc9350a8361d328f))
* wipe per storage type ([#1772](https://github.com/phantomwork/privateGPT/issues/1772)) ([1018250](https://github.com/phantomwork/privateGPT/commit/1018250a300d483560a6d9f948ecede8c0a2f465))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/phantomwork/privateGPT/issues/1841)) ([020be3c](https://github.com/phantomwork/privateGPT/commit/020be3c121bb0410289ed0237526ef0fd87514d5))
* 294 (tested) ([e436eea](https://github.com/phantomwork/privateGPT/commit/e436eea7b6d4b55e19efa6524ec242c2b190332b))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([61cfd2d](https://github.com/phantomwork/privateGPT/commit/61cfd2df0a11948dbce0b363f86e6377e151ed89))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/phantomwork/privateGPT/issues/1519)) ([735972a](https://github.com/phantomwork/privateGPT/commit/735972a39f9a1562f09264c31e2b551647547b5d))
* chromadb max batch size ([#1087](https://github.com/phantomwork/privateGPT/issues/1087)) ([322c470](https://github.com/phantomwork/privateGPT/commit/322c470df20791fbd8495a3b915bbbc19b0d66d4))
* **deploy:** fix local and external dockerfiles ([975cad6](https://github.com/phantomwork/privateGPT/commit/975cad600d60b731825f488261b2350f5c72d6e0))
* Disable Chroma Telemetry ([a72435b](https://github.com/phantomwork/privateGPT/commit/a72435bbe40abecabc59b0259a968f8e064b7594))
* Docker and sagemaker setup ([#1118](https://github.com/phantomwork/privateGPT/issues/1118)) ([4657fa1](https://github.com/phantomwork/privateGPT/commit/4657fa11d66c3541ce60c7269796f576d3629202))
* **docker:** docker broken copy ([#1419](https://github.com/phantomwork/privateGPT/issues/1419)) ([722fc21](https://github.com/phantomwork/privateGPT/commit/722fc21a69ddbc66b14bf04f727a96e9e6e0eda5))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/phantomwork/privateGPT/issues/1779)) ([f90b902](https://github.com/phantomwork/privateGPT/commit/f90b9021322b5ad645a19eb7ba69cde7645ebef8))
* **docs:** Minor documentation amendment ([#1739](https://github.com/phantomwork/privateGPT/issues/1739)) ([ed24310](https://github.com/phantomwork/privateGPT/commit/ed243106c076fd7dc854198cea38243f5409d2c5))
* **docs:** Update installation.mdx ([#1866](https://github.com/phantomwork/privateGPT/issues/1866)) ([2058557](https://github.com/phantomwork/privateGPT/commit/2058557c47c528d2fcc8d10e03e525b4f6b45dbf))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([533ebe4](https://github.com/phantomwork/privateGPT/commit/533ebe4dbe5357006975ee63c36d6076e7995166))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/phantomwork/privateGPT/issues/1123)) ([840a528](https://github.com/phantomwork/privateGPT/commit/840a528930e6a2b91a54ff3f61a92fc7be81aecb))
* Fixed docker-compose ([#1758](https://github.com/phantomwork/privateGPT/issues/1758)) ([688a8cb](https://github.com/phantomwork/privateGPT/commit/688a8cbf205f86a94c0bcbaedea6f0fdc9c3222d))
* **ingest:** update script label ([#1770](https://github.com/phantomwork/privateGPT/issues/1770)) ([fe43ee9](https://github.com/phantomwork/privateGPT/commit/fe43ee958c12e9df873c5be06b6816f3d3847679))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/phantomwork/privateGPT/issues/1954)) ([7357e9e](https://github.com/phantomwork/privateGPT/commit/7357e9e8c3c904409f82190ef8e839cc251f60a9))
* **llm:** special tokens and leading space ([#1831](https://github.com/phantomwork/privateGPT/issues/1831)) ([68b62cd](https://github.com/phantomwork/privateGPT/commit/68b62cdd4e9696d02cd75a55f187a5941de64a78))
* make docs more visible ([#1081](https://github.com/phantomwork/privateGPT/issues/1081)) ([e5c0efc](https://github.com/phantomwork/privateGPT/commit/e5c0efcaadcab4aeb485c9766655484f58291c59))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/phantomwork/privateGPT/issues/1859)) ([7d45c63](https://github.com/phantomwork/privateGPT/commit/7d45c63450c29d4bb43aae4905a205f921e57faa))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/phantomwork/privateGPT/issues/1449)) ([660312a](https://github.com/phantomwork/privateGPT/commit/660312a77300256087997ec1de695528344005a3))
* Remove global state ([#1216](https://github.com/phantomwork/privateGPT/issues/1216)) ([2037964](https://github.com/phantomwork/privateGPT/commit/2037964f1a5dcfcc1e3d8eb0a21c59b5771d61c0))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/phantomwork/privateGPT/issues/1890)) ([94e2c0d](https://github.com/phantomwork/privateGPT/commit/94e2c0d5a858d3d75841d3d4aceb1590af912b98))
* sagemaker config and chat methods ([#1142](https://github.com/phantomwork/privateGPT/issues/1142)) ([ccecbe6](https://github.com/phantomwork/privateGPT/commit/ccecbe63e421b0f2e63baff5656dfae7a8330799))
* **settings:** correct yaml multiline string ([#1403](https://github.com/phantomwork/privateGPT/issues/1403)) ([847c37c](https://github.com/phantomwork/privateGPT/commit/847c37c84103d19f265cb4907e66ee1b1745c1fd))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/phantomwork/privateGPT/issues/1925)) ([cef39f8](https://github.com/phantomwork/privateGPT/commit/cef39f8bae9c27655f5f384025c21cd2514c3f78))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/phantomwork/privateGPT/issues/1709)) ([a05371f](https://github.com/phantomwork/privateGPT/commit/a05371f56f6d3210930980818639bb4dedac3051))
* **tests:** load the test settings only when running tests ([1f0473b](https://github.com/phantomwork/privateGPT/commit/1f0473b86858a12e1d7aef2921ce1026f09178f4))
* typo in README.md ([#1091](https://github.com/phantomwork/privateGPT/issues/1091)) ([545f997](https://github.com/phantomwork/privateGPT/commit/545f99776f720b2bf3aa212239f3807fdf3372b7))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([ce74f41](https://github.com/phantomwork/privateGPT/commit/ce74f41cf44460538dd6d1b5f01264f40fe1d166))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/phantomwork/privateGPT/issues/1260)) ([90799f9](https://github.com/phantomwork/privateGPT/commit/90799f9199d6f3165e84795875b0bc82a18dec8e))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/phantomwork/privateGPT/issues/1280)) ([7f607ce](https://github.com/phantomwork/privateGPT/commit/7f607ce3599423aee740f94acd5f0bb51e384fcd))


### Miscellaneous Chores

* Initial version ([5477dfc](https://github.com/phantomwork/privateGPT/commit/5477dfc3c7468b87110c3c855edf83b0e0cb71f7))

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
