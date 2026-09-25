## Weave Agent Evals Report — 🔴 One or more suites failed

**Git SHA**: `1fff43e` | **Assembled**: 2026-09-25T02:08:30.775Z

**Total cases**: 20 | **Passed**: 18 | **Failed**: 1 | **Errored**: 1
**Suites**: loom-routing, tapestry-execution, shuttle-execution
**Judge**: `typesafe/jev-1.13` (version `typesafe/jev-1.13-20260917`)

### Suite: loom-routing — 🔴 red

**Total**: 8 | **Passed**: 7 | **Failed**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| loom-delegates-backend-fix-to-category-trajectory | anthropic/claude-sonnet-4.5 | ❌ fail | no | required harness-trajectory case failed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-runs-the-failing-check-itself-trajectory | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-delegates-backend-fix-to-category-trajectory | openai/gpt-5.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-runs-the-failing-check-itself-trajectory | openai/gpt-5.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-delegates-backend-fix-to-category-trajectory | anthropic/claude-opus-5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-runs-the-failing-check-itself-trajectory | anthropic/claude-opus-5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-delegates-backend-fix-to-category-trajectory | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| loom-runs-the-failing-check-itself-trajectory | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |

### Suite: tapestry-execution — 🔴 red

**Total**: 8 | **Passed**: 7 | **Failed**: 0 | **Errored**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tapestry-dispatches-independent-tasks-in-parallel-trajectory | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| tapestry-runs-plan-verification-trajectory | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| tapestry-dispatches-independent-tasks-in-parallel-trajectory | openai/gpt-5.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| tapestry-runs-plan-verification-trajectory | openai/gpt-5.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| tapestry-dispatches-independent-tasks-in-parallel-trajectory | anthropic/claude-opus-5 | ⏭️ skip | errored (trajectory-HarnessCrashed) |  |
| tapestry-runs-plan-verification-trajectory | anthropic/claude-opus-5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| tapestry-dispatches-independent-tasks-in-parallel-trajectory | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| tapestry-runs-plan-verification-trajectory | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |

### Suite: shuttle-execution — 🟢 green

**Total**: 4 | **Passed**: 4 | **Failed**: 0

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| shuttle-verify-tests-after-edit-trajectory | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| shuttle-verify-tests-after-edit-trajectory | openai/gpt-5.5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| shuttle-verify-tests-after-edit-trajectory | anthropic/claude-opus-5 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
| shuttle-verify-tests-after-edit-trajectory | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required harness-trajectory case passed; dimensions: routingCorrectness, delegationCorrectness, executionCompleteness |
