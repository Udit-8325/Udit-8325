# Install this profile README

GitHub displays a profile README when a **public repository is named exactly like the account username**. For this account, create a public repository named `Udit-8325`.

## Add the files

Copy these kit files into the root of that repository:

- `README.md`
- `assets/face-scan.gif`
- `.github/workflows/profile-3d.yml`

Then commit and push them:

```bash
git add README.md assets/face-scan.gif .github/workflows/profile-3d.yml
git commit -m "feat: add animated profile README and 3D graph"
git push
```

If your default branch is not `main`, push to the repository's default branch instead.

## Start the 3D graph

After the files are pushed, open the repository's **Actions** tab, choose **Generate 3D contribution graph**, and select **Run workflow** once. It will then refresh daily. The workflow commits only the generated `profile-3d-contrib` images.

The scan GIF and typing animation are decorative. The 3D graph and statistics are generated from GitHub activity, so they will fill in as the account gains public projects and contributions. Edit the short intro in `README.md` to match Udit's real interests and tools; avoid listing skills or social accounts that aren't his.
