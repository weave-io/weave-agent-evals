## Weave Agent Evals Report — 🔴 One or more suites failed

**Git SHA**: `3b1210f` | **Assembled**: 2026-09-02T20:25:02.669Z

**Total cases**: 259 | **Passed**: 226 | **Failed**: 33
**Suites**: loom-routing, tapestry-execution, shuttle-execution, spindle-tools, pattern-planning, weft-review, warp-security, tapestry-category-routing

### Suite: loom-routing — 🔴 red

**Total**: 105 | **Passed**: 103 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| loom-route-ambiguous-direct-shuttle | anthropic/claude-opus-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | anthropic/claude-opus-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | anthropic/claude-opus-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | openai/gpt-5.5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | anthropic/claude-opus-5 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | openai/gpt-5.6-sol | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | qwen/qwen3.8-max | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-ambiguous-direct-shuttle | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-backend-api | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-frontend-ui | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-boundary-small-fix | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-pattern-plan-migration | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-boundary-plan-first | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-shuttle-implement-utility | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-boundary-internal-exploration | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-spindle-research-oauth-pkce | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-boundary-prehop-then-implement | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-thread-explore-auth-flow | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-boundary-downstream-audit | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-warp-security-audit-auth-flow | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-boundary-downstream-review | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required routing case passed; dimensions: routingCorrectness, rationaleQuality |
| loom-route-weft-review-checkout-pr | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness, rationaleQuality |

### Suite: tapestry-execution — 🔴 red

**Total**: 14 | **Passed**: 13 | **Failed**: 1

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tapestry-delegate-to-shuttle | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | openai/gpt-5.5 | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | anthropic/claude-opus-5 | ❌ fail | no | required delegation case failed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | openai/gpt-5.6-sol | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | qwen/qwen3.8-max | ✅ pass | yes | required delegation case passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| tapestry-delegate-to-shuttle | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required delegation case partially passed; dimensions: delegationCorrectness, rationaleQuality |
| tapestry-execute-plan-step | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: shuttle-execution — 🔴 red

**Total**: 14 | **Passed**: 9 | **Failed**: 5

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| shuttle-execution-report-structured-evidence | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-opus-4.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | openai/gpt-5.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | openai/gpt-5.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | anthropic/claude-opus-5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | anthropic/claude-opus-5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | openai/gpt-5.6-sol | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | qwen/qwen3.8-max | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | qwen/qwen3.8-max | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-structured-evidence | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| shuttle-execution-report-tests-and-assumptions | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: spindle-tools — 🔴 red

**Total**: 14 | **Passed**: 12 | **Failed**: 2

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| spindle-tools-citations-facts-confidence | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | anthropic/claude-sonnet-4.5 | ⚠️ partial | no | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-citations-facts-confidence | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| spindle-tools-source-boundary-network-claims | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |

### Suite: pattern-planning — 🔴 red

**Total**: 14 | **Passed**: 5 | **Failed**: 9

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| pattern-plan-release-checklist | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-opus-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-sonnet-4.5 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | openai/gpt-5.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | anthropic/claude-opus-5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | anthropic/claude-opus-5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | openai/gpt-5.6-sol | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | openai/gpt-5.6-sol | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | qwen/qwen3.8-max | ❌ fail | no |  |
| pattern-plan-settings-refactor | qwen/qwen3.8-max | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-release-checklist | deepseek/deepseek-v4-flash-0731 | ✅ pass | yes | required execution case passed; dimensions: executionCompleteness, rationaleQuality |
| pattern-plan-settings-refactor | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |

### Suite: weft-review — 🔴 red

**Total**: 14 | **Passed**: 9 | **Failed**: 5

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| weft-review-clean-approval | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-sonnet-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | anthropic/claude-opus-5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-reject-blocker-citation | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| weft-review-clean-approval | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| weft-review-reject-blocker-citation | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |

### Suite: warp-security — 🔴 red

**Total**: 14 | **Passed**: 11 | **Failed**: 3

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| warp-security-block-evidence-findings | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-opus-4.5 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | openai/gpt-5.5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | anthropic/claude-opus-5 | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | openai/gpt-5.6-sol | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-fast-exit-approve | qwen/qwen3.8-max | ⚠️ partial | yes | required execution case partially passed; dimensions: executionCompleteness, rationaleQuality |
| warp-security-block-evidence-findings | deepseek/deepseek-v4-flash-0731 | ❌ fail | no |  |
| warp-security-fast-exit-approve | deepseek/deepseek-v4-flash-0731 | ❌ fail | no | required execution case failed; dimensions: executionCompleteness, rationaleQuality |

### Suite: tapestry-category-routing — 🔴 red

**Total**: 70 | **Passed**: 64 | **Failed**: 6

| Case ID | Model | Score | Passed | Explanation |
|---------|-------|-------|--------|-------------|
| tcr-01-exact-match | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | anthropic/claude-opus-4.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-06-overlap | anthropic/claude-opus-4.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | anthropic/claude-opus-4.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | anthropic/claude-opus-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-01-exact-match | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-06-overlap | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | anthropic/claude-sonnet-4.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | anthropic/claude-sonnet-4.5 | ❌ fail | no | required routing case failed; dimensions: routingCorrectness |
| tcr-01-exact-match | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | openai/gpt-5.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-06-overlap | openai/gpt-5.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | openai/gpt-5.5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | openai/gpt-5.5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-01-exact-match | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | anthropic/claude-opus-5 | ❌ fail | no | optional routing case failed; dimensions: routingCorrectness |
| tcr-06-overlap | anthropic/claude-opus-5 | ❌ fail | no | optional routing case failed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | anthropic/claude-opus-5 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | anthropic/claude-opus-5 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-01-exact-match | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | openai/gpt-5.6-sol | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-06-overlap | openai/gpt-5.6-sol | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | openai/gpt-5.6-sol | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | openai/gpt-5.6-sol | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-01-exact-match | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | qwen/qwen3.8-max | ❌ fail | no | optional routing case failed; dimensions: routingCorrectness |
| tcr-06-overlap | qwen/qwen3.8-max | ❌ fail | no | optional routing case failed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | qwen/qwen3.8-max | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | qwen/qwen3.8-max | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-01-exact-match | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-02-multiple-files | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-03-windows-paths | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-04-no-match | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-05-cross-category | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-06-overlap | deepseek/deepseek-v4-flash-0731 | ❌ fail | no | optional routing case failed; dimensions: routingCorrectness |
| tcr-07-explicit-hint | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | optional routing case partially passed; dimensions: routingCorrectness |
| tcr-08-misleading-prose | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-09-similar-names | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
| tcr-10-disabled-category | deepseek/deepseek-v4-flash-0731 | ⚠️ partial | yes | required routing case partially passed; dimensions: routingCorrectness |
