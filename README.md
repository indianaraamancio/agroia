# agroia - Question-answering System for Field Technicians using Artificial Intelligence
Files from the Agro.IA question-answering system: RAG pipeline; data ingestion; ROUGE-1 metric data.

# agroia_rag.zip
To run it, you must give execution permission to the .sh files with:
chmod +x final_script.sh
chmod +x script.sh
Then, uncomment the execution lines (the ones that call the initialize_model() and search() functions) and insert your Hugging Face token in the login() line (uncommenting it as well). After that, run the following command:
nohup ./final_script.sh
The version with the Rouge and Nemenyi tests can be found in the "completo" branch of this repository.
