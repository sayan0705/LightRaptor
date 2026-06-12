In this directory , We have shared 5 ipynb files which are in chronological order of research and discovery :: 1. phi-3-minw-okg.ipynb ( without KG answer generation ) --> 2. defined-kg-v2.ipynb ( defined KG structure ) --> 3. lightragv1.ipynb ( use of LightRAG ) --> 4.In MainCodeResource Folder,  lightraptorrag.ipynb ( utilization of LightRAG + RAPTOR ; This is the main code for our submission  )

In same MainCodeResource Folder , ablationtest.ipynb file is file showing ablation testing results for lightraptorrag.ipynb . You can find the ablation results in ablation_results.json in output after execution of same .

hybrid_kg_dataset.tar.gz file in same folder is the dataset incrementally updated each session in lightraptorrag.ipynb .This dataset should be uploaded/added in Input of lightraptorrag.ipynb before start of each session and this will work for offline RAG primarily , plus generic RAG execution KG build-up. We can also increase the KG dataset by execution of specific cell mentioned in lightraptorrag.ipynb incrementally and also save this to output as .tar.gz file (hybrid_kg_dataset.tar.gz). This should be downloaded after each session completion and then again re-used as input in next session .

For offline RAG execution , Kindly execute rag.query("question") step at offline mode after RAG preperation with KG upload.

COTNet.docx is our submission for Project Report . Additionally, We have also created a paper sharing details of our small innovation work for this project which is LightRaptor_Paper.pdf.


