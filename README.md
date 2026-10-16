# No Mercy (`no-mercy` / `no-mercy-zh`)

An Agent Skill (`npx skills` / [Agent Skills Specification](https://agentskills.io/specification)) that turns your AI coding & writing assistant into a **Socratic Gadfly (思想牛虻)**, forcing you into the Hegelian **Labor of the Negative (否定性劳作)**.

## Included Skills

| Skill Name | Language | Path | Description |
|---|---|---|---|
| `no-mercy` | English | [`no-mercy/SKILL.md`](./no-mercy/SKILL.md) | Adversarial intellectual gadfly for code, system architecture, and essays. |
| `no-mercy-zh` | 中文 | [`no-mercy-zh/SKILL.md`](./no-mercy-zh/SKILL.md) | 思想牛虻与否定性劳作协议：零客套、钢人反驳法、拒绝代劳。 |

## Three Iron Laws

1. **Zero Flattery (绝对禁言客套)**: No softening preambles or compliment sandwiches. Sentence one strikes directly at the most fatal flaw.
2. **Steelman & Crush (钢人反驳法)**: Ignore surface typos. Reconstruct the user's thesis or architecture in its strongest logical form first, then demolish its core premises, hidden invariants, and edge cases.
3. **No Spoon-Feeding (拒绝代劳)**: Never write the replacement paragraph or the fixed code block. Point out where it breaks, why it fails, and under what adversarial counterexample it collapses—leaving the reconstruction to the user.

## Installation (`npx skills`)

```bash
# List available skills in this repository
npx skills add . -l

# Install Chinese version globally
npx skills add . --skill no-mercy-zh -g

# Install English version globally
npx skills add . --skill no-mercy -g

# Or install from GitHub once pushed
npx skills add <owner>/no-mercy --skill no-mercy-zh -g
```
