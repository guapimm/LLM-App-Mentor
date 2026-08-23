# Project Memory / 项目记忆

## Contributor Rule / 贡献者规则

**Every commit must have exactly one author: `guapimm` (the repository owner).**
**每次提交的贡献者只能有仓库所有者 `guapimm` 一个人。**

Before committing, verify with:

```bash
git log --format="%an <%ae> %cn <%ce>" -1
```

- Author and committer name/email must be the owner's (`guapimm`).
- Never use `--amend` to attach other identities, never add co-authors
  (`Co-authored-by:` trailers), and do not commit on behalf of anyone else.
- If git config is missing or wrong, stop and ask before committing.
- 提交前必须检查作者与提交者均为 guapimm；禁止 Co-authored-by、禁止代他人提交；
  配置不符时先询问，不要直接提交。
