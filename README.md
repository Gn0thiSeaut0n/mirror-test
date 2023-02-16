# mirror-test

### 1. 원본 저장소 복사

    git clone --mirror [original repository path]

### 2. 해당 폴더 안으로 진입

    cd [original repository name].git
    
### 3. 깃허브에 폴더 하나 생성 후 주소 삽입

    git remote set-url --push origin [remote repository path]

### 4. push

    git push --mirror
