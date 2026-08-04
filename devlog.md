# Dev Log

## 2026-08-04
- Selected ARC-AGI-3-Agents (https://github.com/arcprize/ARC-AGI-3-Agents?tab=MIT-1-ov-file) as the base project to develop further. Followed the original README.md to set up the environment. Since the project itself has already been managed by uv, 
  ```bash
  uv add XXX
  ```
  command is used every time an uninstalled library is required.
- Downloaded competition files by running competition_download.py. Copied environment_files directory to project directory.

- Changed the remote repository.
  ```bash
  git remote set-url origin git@github.com:SophiaShuangWu/arc-agi-3-agents.git
  git remote -v
  git push -u origin main
  ```

## 2026-08-03
- Played through all 25 public games on the official website(https://arcprize.org/tasks) to build intuition for the task types.