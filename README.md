# GradeBook Package

`gradebook`은 학생들의 성적 데이터를 관리하고, 평균 및 학점을 계산하며 CSV 파일 입출력을 지원하는 파이썬 성적 관리 패키지입니다.

---

## 📁 프로젝트 구조

```text
project_root_pkg/
├── gradebook/
│   ├── __init__.py
│   ├── __main__.py
│   ├── cli.py
│   ├── models.py
│   ├── utils.py
│   └── io/
│       ├── __init__.py
│       └── csvio.py
├── tests/
│   └── test_utils.py
├── students.csv
├── .gitignore
└── README.md
