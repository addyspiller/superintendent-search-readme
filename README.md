# Superintendent Evaluation Tool

A more consistent, defensible way for a co-op board to evaluate superintendent candidates.

## The problem

I built this while my co-op board was hiring a new building superintendent.

Historically, candidates had been evaluated somewhat differently depending on who interviewed them and when. Information lived across resumes, conversations, reference calls, and people's memories, making it difficult to compare candidates consistently or go back later and understand why someone had advanced or been rejected.

The challenge wasn't simply organizing candidate information. It was creating a better decision process.

## Product decisions

I designed the workflow around a few principles:

- **Filter hard requirements first.** Candidates who don't meet non-negotiable requirements shouldn't consume the board's interview time.
- **Evaluate everyone against the same criteria.** Resumes and interviews use a consistent, building-specific framework rather than shifting standards from candidate to candidate.
- **Use AI to support judgment, not replace it.** AI surfaces relevant experience and potential gaps, but the board makes the hiring decision.
- **Keep the decision trail together.** Resume evaluation, interview notes, references, scoring, and offers live in one place so the board doesn't have to reconstruct what happened later.
- **Design for the actual building.** Evaluation criteria reflect the realities of the property, from pre-war building systems and NYC compliance to staff supervision and commercial tenant coordination.

## What I built

The application supports the full superintendent hiring process:

1. Upload a candidate resume
2. Evaluate hard requirements and building-specific experience
3. Conduct structured interviews using a common rubric
4. Track references and outcomes
5. Record in-person sessions and notes
6. Compare candidates side by side
7. Track offers and the final hiring decision

Candidate information sits behind authentication to protect PII.

## What happened

The board used the tool throughout the superintendent search, creating a much more structured evaluation process than we had used previously.

It also surfaced a broader use case: our property manager saw enough value in the approach that she wanted to use it for superintendent searches at other buildings she manages.

## Built with

React · Vite · Firebase · Claude API
