# Joint CI PR body template (Driver)

```
CI_MODE=joint
JOINT_WAIT=true
JOINT_CI_ID=exp-YYYYMMDD-NNN
DEPENDS_ON: zhekui-hub/joint-ci-synapse@<branch>
```

- `joint-ci` Required check = Arsenal **public tests only** (written back by lab)
- `driver-precheck` / `driver-independent-ci` = this repo
