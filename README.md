# Belief Polarization Under Misinformation Simulation

## Project Overview

This project presents an agent-based simulation modeling belief polarization within social networks, focusing on the impact of different information ecosystems, particularly the presence of misinformation. It explores how individual agent beliefs and network interactions evolve under varying information quality.

## Key Components

*   **`InformationSource`**: Simulates various information channels (scientific, media, social) with defined credibility, bias, and misinformation levels.
*   **`IdentityAgent`**: Represents individuals with a `belief` (stance on a topic) and `lambda_i` (identity, resistance to belief change), categorized as accepting, hesitant, or resistant.
*   **`InformationEcosystem`**: Configures and manages information sources based on predefined scenarios (Optimal, Realistic, Misinformation).
*   **`IdentityBeliefSimulation`**: The core simulation engine that orchestrates agent interactions, information consumption, and belief updates within a social network.

## Simulation Scenarios

1.  **Optimal**: Ideal information environment with high credibility and low misinformation.
2.  **Realistic**: Represents typical information landscapes with mixed credibility and moderate misinformation.
3.  **Misinformation**: Simulates an environment dominated by high levels of misinformation and reduced source credibility.

## Key Metrics & Visualizations

The simulation tracks and visualizes:

*   **Acceptance, Accuracy, Polarization**: Time-series plots showing the evolution of these metrics.
*   **Per-type Acceptance**: Acceptance rates broken down by agent archetypes.
*   **Final Belief Distributions**: KDE plots of agent beliefs at the simulation's end.
*   **Social Network**: Visualizations of the network structure, colored by agent beliefs and types.
*   **Sensitivity Analysis**: Plots and heatmaps exploring the impact of key parameters (e.g., homophily, agent identity) on simulation outcomes.
