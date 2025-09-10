# Git이란 무엇일까요? (What is Git?)

## Git이란? (Git 개념)

Git은 **분산 버전 관리 시스템(Distributed Version Control System, DVCS)**입니다. 쉽게 말해, 프로젝트 파일의 변경 사항을 시간에 따라 사진 찍듯이 기록하고 관리하며, 여러 개발자가 효율적으로 협업할 수 있도록 돕는 도구입니다.

### 실생활 비유: 마법 같은 공동 집필 노트

여러 명의 작가가 모여 하나의 책을 쓴다고 상상해 보세요.

- **커밋(Commit)**: 작가가 한 챕터를 완성할 때마다, 노트에 '챕터 3 초안 완성'이라는 메모와 함께 완성된 원고를 그대로 복사해서 붙여넣습니다. 이렇게 각 변경 단계를 저장하는 행위가 '커밋'입니다.
- **브랜치(Branch)**: 한 작가가 기존 스토리와 다른 새로운 결말을 구상하고 싶어졌습니다. 그는 원래 노트에 영향을 주지 않기 위해, 노트를 한 권 복사해서(새로운 '브랜치'를 만들어서) 그곳에 새로운 아이디어를 마음껏 실험합니다.
- **병합(Merge)**: 새로운 결말이 반응이 좋아서 원래 스토리에 합치기로 결정했습니다. 복사했던 노트의 변경 사항을 원래 노트에 합치는 과정이 '병합'입니다.
- **분산(Distributed)**: 모든 작가가 각자 자신만의 완전한 노트 복사본을 가지고 있습니다. 인터넷이 안 되는 곳에서도 자유롭게 글을 쓰고 저장(커밋)할 수 있으며, 나중에 함께 모였을 때 각자의 변경 사항을 중앙 노트에 동기화할 수 있습니다.

이처럼 Git은 코드의 변경 이력을 모두 기록하여 언제든 원하는 시점으로 되돌아갈 수 있게 해주고(안정성), 다른 사람의 작업에 영향을 주지 않으면서 새로운 기능을 독립적으로 개발할 수 있게 하여(협업 효율성) 개발자에게 필수적인 도구로 자리 잡았습니다.

---

## What is Git? (The Concept of Git)

Git is a **Distributed Version Control System (DVCS)**. In simple terms, it's a tool that helps you track changes in your project files over time—like taking snapshots—and enables multiple developers to collaborate efficiently.

### Real-life Analogy: A Magical Collaborative Writing Notebook

Imagine several authors collaborating on a single book.

- **Commit**: Whenever an author finishes a chapter, they save a snapshot of the entire manuscript at that moment with a note like, "Wrote the first draft of Chapter 3." This action of saving a specific version is a 'commit'.
- **Branch**: An author wants to experiment with a different ending without disturbing the main story. They create a copy of the notebook (a new 'branch') to freely test their new ideas.
- **Merge**: If the new ending is well-received, they decide to incorporate it into the main story. The process of combining the changes from the copied notebook back into the original is a 'merge'.
- **Distributed**: Every author has their own complete copy of the notebook. They can write and save their progress (commit) even when offline, and later sync their changes with a central, master notebook when they get together.

Like this, Git has become an essential tool for developers because it provides stability by recording all change history (allowing you to revert to any point in time) and boosts collaborative efficiency by enabling independent feature development without interfering with others' work.

---

## 추가 학습 개념 (Next Concepts to Learn)

- **Repository**: 프로젝트의 모든 파일과 변경 이력이 저장되는 공간 (저장소)
- **Staging Area**: 커밋할 변경 사항들을 미리 모아두는 준비 영역
- **Git 주요 명령어 (Key Commands)**: `add`, `commit`, `push`, `pull`, `branch`, `merge`
- **GitHub, GitLab, Bitbucket**: Git 저장소를 관리하고 협업 기능을 제공하는 웹 기반 호스팅 서비스
