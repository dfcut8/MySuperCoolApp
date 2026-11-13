# Project React Native skills

These skills are installed locally in `.agents/skills` and checked into this repository. Codex discovers this directory automatically; the skills are available on the next turn. See the [official skills documentation](https://learn.chatgpt.com/docs/build-skills).

## Installed skills

| Skill | Use it for | Source at the installed commit |
| --- | --- | --- |
| `vercel-react-native-skills` | React Native components, lists, navigation, animations, and UI patterns; also covers Expo. | [Vercel](https://github.com/vercel-labs/agent-skills/tree/1a2c79d4e6c4a2283dc2c614b6538cbe1ed5ca62/skills/react-native-skills) |
| `react-native-best-practices` | Profiling and measured improvements to rendering, startup time, memory, and bundle size. | [Callstack Incubator](https://github.com/callstackincubator/agent-skills/tree/59e9d17446a248b21d86f078fcd0bd2d36db1ca4/skills/react-native-best-practices) |
| `react-native-testing` | Component tests with React Native Testing Library, including version-specific v13/v14 guidance. | [Callstack](https://github.com/callstack/react-native-testing-library/tree/564a84294717d8e4b0831f3e3a5e115cc3832e01/skills/react-native-testing) |
| `upgrading-react-native` | React Native upgrades, native template changes, dependency compatibility, and upgrade verification. | [Callstack Incubator](https://github.com/callstackincubator/agent-skills/tree/59e9d17446a248b21d86f078fcd0bd2d36db1ca4/skills/upgrading-react-native) |

Selected on 2026-11-13 after reviewing the skill instructions, upstream maintainers, repository activity, and adoption on [skills.sh](https://skills.sh/). Together they cover everyday development, performance diagnosis, component testing, and framework upgrades. The performance guide links to the companion upgrade skill, which is included to keep that reference usable locally.

Codex can select a skill when a task matches its description. To request one explicitly, include its name in your prompt, for example: `Use $react-native-testing to test the parcel form.`

Apply guidance to the project's actual dependency versions and chosen stack. Expo-specific suggestions apply when Expo is in use. For performance work, use Callstack's measure-first workflow before adopting optimizations from either guide.

## Provenance and updates

The complete skill directories were copied without modification using Codex's bundled `skill-installer/scripts/install-skill-from-github.py`, with `--ref` set to the commits linked above and `--dest .agents/skills`. The Vercel installation also used `--name vercel-react-native-skills` to match its declared skill name. No global skill installation is required.

To update, review the upstream changes, choose a new commit, and use the installer to download the complete skill directory into a temporary destination. Compare it with the installed copy, replace the intended skill, preserve its license notices, and update the pinned source link here in the same pull request. The installer refuses to overwrite an existing skill directory.

Callstack's repository-level MIT licenses are included as `LICENSE` in their respective skill directories. Vercel declares `license: MIT` in its `SKILL.md`; its repository does not supply a separate license file at the pinned commit.
