# Furhat Healthcare HRI Experiment

A human-robot interaction study investigating how **facial expressions** and **empathetic language** influence user trust, perceived empathy, and stress during a simulated hospital triage interaction.

> **Academic project developed collaboratively at Vrije Universiteit Amsterdam.**

## Overview

This project explores how different conversational and non-verbal behaviours of a social robot affect how users perceive and respond to it.

The study used a **Furhat social robot** to simulate an emergency-room check-in interaction. Four experimental conditions were developed by varying:

- Facial expressions
- Conversational language style

The goal was to investigate whether combining verbal empathy with non-verbal emotional expression produces a stronger effect than using either alone.

## Research Question

> **How do facial expressions and empathetic language influence perceived empathy, trust, and stress during a simulated hospital triage interaction?**

## Experimental Conditions

Four interaction conditions were implemented:

| Condition | Facial Expressions | Language |
|---|---|---|
| Basic | No | Functional |
| Emotions Only | Yes | Functional |
| Friendly Voice Only | No | Empathetic |
| Final | Yes | Empathetic |

The prototypes were designed to isolate the effects of the two independent factors and their combination.

## Furhat Prototypes

The interaction prototypes are included in the [`prototypes`](prototypes/) directory.

### Basic Prototype

The baseline interaction uses functional language without additional emotional facial expressions.

### Emotions Only

This condition introduces facial expressions while maintaining the functional conversational style.

### Friendly Voice Only

This condition introduces more empathetic language while keeping the robot's facial behaviour neutral.

### Final Prototype

The final condition combines **empathetic language and facial expressions**.

## Study Design

The study used a between-subjects experimental design with:

- **20 participants**
- **4 experimental conditions**
- **5 participants per condition**

Participants interacted with the Furhat robot in a simulated emergency-room check-in scenario and subsequently completed a questionnaire measuring their perceptions of the interaction.

The questionnaire used 5-point Likert-scale items covering aspects including perceived empathy, trust, and emotional response.

## Results

The reported composite scores for the four conditions were:

| Condition | Mean Composite Score |
|---|---:|
| Basic | 1.67 |
| Emotions Only | 2.07 |
| Friendly Voice Only | 3.53 |
| Final | 4.60 |

The analysis reported a significant overall difference between the experimental conditions (**Kruskal–Wallis adjusted p < 0.001**).

The results suggested that **empathetic language had a substantially stronger effect than facial expressions alone**, while combining empathetic language with facial expressions produced the highest overall scores.

## My Contribution

I designed and implemented the Furhat interaction prototypes used in the experiment, including the different facial-expression and language conditions.

I also contributed to:

- Experimental design
- Study implementation
- Participant data collection
- Data analysis
- Research writing and formatting

## Technologies & Concepts

### Human-Robot Interaction

- Furhat social robot
- Conversational interaction
- Socially expressive robotics
- Human-centred AI

### Research

- Experimental design
- Between-subjects study
- User studies
- Likert-scale questionnaires
- Non-parametric statistical analysis
- Human-subject evaluation

## Project Structure

```text
furhat-healthcare-hri/
├── README.md
├── prototypes/
│   ├── Basic prototype.xml
│   ├── Emotions only prototype.xml
│   ├── Friendly voice only prototype.xml
│   └── Final (emotions and language) prototype.xml
└── figures/
```

## Academic Context

This project was developed as part of an academic human-robot interaction project at **Vrije Universiteit Amsterdam**.

The project investigates how verbal and non-verbal behaviours can influence human perception of social robots in a healthcare-related interaction.