## Create Name Repositories

*project name-( frontend or backend )-( language or framework )*

**Example**

`read-csv-backend-python`

## How to write README in Repositories

**Project setup**
- package intall
- python project `Create venv for pip install(requirements.txt)`
- Java script(backend) recomend `npm`
- Java script(frontend) recomend `yarn`

**Recomend stack version**

- python require version 3.10.11
- node.js require v20 or higther

**Document**

*Example: API Project*
- API Reference
- Deployment
- Link

## Write Git Commit Message
- `build:` อะไรก็ตามที่มันเกี่ยวกับการ Build (เช่น คำสั่ง npm หรือการเพิ่ม External Dependencies)
- `chore:` อะไรก็ตามที่ไม่เห็นจากข้างนอก (เช่น การปรับ .gitignore หรือ .prettierrc file)
- `feat:` A new feature
- `fix(optional):` A bug fix
- `docs:` อะไรก็ตามที่เกี่ยวกับการปรับเอกสาร
- `refactor:` การปรับปรุงโค้ด เพื่อลดความซับซ้อนในการอ่านและเขียนของฟังก์ชั่นการทำงาน รวมทั้งลบฟังก์ชั่นที่ไม่ได้ถูกเรียกใช้
- `perf:` อะไรก็ตาม ที่เกี่ยวกับการปรับปรุงประสิทธิภาพของตัว Application
- `test:` อะไรก็ตาม ที่เกี่ยวกับการทดสอบ 

## Git Ignore

**Python Project**
- pycache
- venv
- .vscode

**Java script Project**
- node_modules
- .vscode
