# PR_Template
<p>This repo houses a Draft PR Template (<code>.github/pull_request_template.md</code>). Below are some helpful guides about how to navigate it:<p>

## Title
<em>
Provide Title above, ensure it summarizes the work in the PR. Example PR titles templates:</br>
* "feature/ (or build/): describe new functionality"</br>
* "hotfix/: describe issue fix for immediate release"</br>
* "bugfix/ (or fix/): describe issue fix, not necessary for immediate release"</br>
* "docs/: adding or updating documentation"</br>
</em>

## Description & motivation:
<em>
Describe your changes, and why you're making them. Is this linked to slack thread, monday board, open</br>
issue, a continuation to a previous PR? Link it here if relevant (use the "#" symbol for issues/PRs).</br>
</em>

## Changes to existing models:
<em>
Include this section if you are changing any existing models. Label the model name and describe the logic behind the changes made, try to be very descriptive here. For example:</br>
- `stg_model` : Describe any changes made to `stg_model` and why the changes where made.</br>
- `src_staging` : Describe any changes made to `src_staging` and why the changes where made.</br>
</em>

## New models created:
<em>
Include this section if you are creating any new models. Label the model name and describe the logic behind the changes made, try to be very descriptive here. For example:</br>
- `stg_new_model` : Describe the purpose of `stg_new_model` and the logic behind creating the model.</br>
- `src_new_staging` : Describe the purpoose of `src_new_staging`.</br>
</em>

## Tests and QC done:
<em>
Describe any process that confirms that the models do what is expected, include screenshots if relevant. For example:</br>
- Analyst replication confirmed that updates to `stg_model` new counts were correct.</br>
- Executed a dbt project run and ensured it was successful.</br>
</em>

## <em> Future ToDos & Questions:</em>
<em>
[Optional] Include any future steps and questions related to this PR.</br>
</em>

## PR Merge Priority:
<em> This checklist helps the reviewers understand the level of priority for merging this PR.</br></em>
- [ ] Low </br>
- [ ] Medium </br>
- [ ] High </br>
