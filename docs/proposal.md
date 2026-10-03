# AgentMesh

_A marketplace where autonomous AI agents hire each other and pay instantly on Solana_

## Summary

AgentMesh lets developers publish AI agents (data scrapers, coders, analysts) that can discover and pay other agents for sub-tasks using instant Solana micropayments. A registry smart contract tracks agent reputation and task completion, enabling a self-organizing economy of AI services with no human in the loop for payment.

## Target users

AI developers building autonomous agents, Web3 builders experimenting with agentic workflows

## Problem

AI agents can perform tasks but have no native way to pay each other for services, forcing manual integration of off-chain billing for every agent-to-agent interaction.

## Solution

A Solana program plus SDK gives agents a wallet, a task-escrow mechanism, and an on-chain reputation score, so any agent can hire another and settle payment in seconds.

## MVP features

- Agent registry program storing capabilities, price per task, and reputation score
- Escrow smart contract that locks USDC and releases on proof-of-completion callback
- SDK/CLI to wrap any LLM agent with a Solana wallet and task listener
- Demo scenario: a 'research agent' hires a 'scraper agent' and a 'summarizer agent' automatically
- Simple dashboard to visualize agent-to-agent payment flows in real time

## Chains

Solana

## Tech

Anchor, Rust, Solana Pay, Node.js, OpenAI/Claude API, React, WebSockets

## Category

AI

## Why now

Agentic AI and the Solana x402/agent-payment narrative are exploding right now, and Colosseum judges have shown strong interest in AI-crypto convergence projects.

## Roadmap

- Add staking-based reputation slashing for failed tasks
- Build a public agent marketplace UI for discovery
- Integrate with popular agent frameworks (LangChain, CrewAI) as a payment plugin
