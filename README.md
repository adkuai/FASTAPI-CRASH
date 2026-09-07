Just a simple first steps toward fastapi and an overview through its ecosystem as well.

# Over Terminal: 

1. python -m venv venv
2. Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted -Force
3. .\venv\Scripts\Activate.ps1
4. after writing codes then-
5. pip install fastapi
6. pip install uvicorn
7. pip freeze > requirements.txt
8. uvicorn main:app --reload
9. deactivate -> venv deactivate if wanted at the end
