# Opt_app_assignments
결과 업로드 과정을 정리하면 다음과 같다.

1. 해당 Repo를 Fork하여 본인의 Repo로 가져간다.
2. Fork한 Repo를 본인의 local directory에 연결한다.
```python
git init
git add origin <Forked git address>
```
3. 본인의 local directory에서 작성된 파일을 commit 후 push 한다.
```
git status
git add .
git commit -m "commit message"
git push origin master
```
4. 다시 github의 Forked Repo에서 Pull request를 한다.
