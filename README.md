# weektwoo5542
results table
<img width="1906" height="209" alt="image" src="https://github.com/user-attachments/assets/83116c85-b6a0-4f48-8c4c-e89c7c54ff12" />


Screenshot 1: Chunking Comparison
<img width="796" height="203" alt="image" src="https://github.com/user-attachments/assets/5466bf74-78ab-440a-9ad8-a89e54f7711a" />

Screenshot 2: Re-ranking
<img width="1667" height="474" alt="image" src="https://github.com/user-attachments/assets/d0af825d-1fdd-455d-82dd-0ebbe7dc1a10" />
full result is text file labeled "Device set to use cpu"

Screenshot 3: Prompt-only vs RAG Answer
<img width="1785" height="583" alt="image" src="https://github.com/user-attachments/assets/f0b4fe94-3bc6-42d6-8899-40220e64a6d4" />

Failure case? = The system failed to generate a clear grounded answer for the ambiguous query about whether to use a fork or a branch

Which layer failed? = The generation layer failed, even though the relevant evidence was retrieved correctly

System-level fix? = This could maybe be fixed by using a stronger language model or reducing the amount of context passed to the generator to avoid token length issues
