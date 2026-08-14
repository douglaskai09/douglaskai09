# Vehicle Business Opportunity Planner — Case Study

## Overview

This project started with a simple question: how can someone choose a pickup truck or other vehicle based not only on purchase price, but on the income opportunities that vehicle can realistically support?

The solution direction became a picture-first business planning system that connects a vehicle's year, size and capabilities to practical service opportunities, operating considerations and simple profit estimates.

The goal was intentionally different from building a dense finance dashboard. The experience was designed to be easy enough for a first-time entrepreneur to understand quickly.

## Problem

Vehicle purchase decisions are often separated from business planning.

A buyer may know they want a truck, van or SUV but still lack a clear answer to questions such as:

- What work can this specific vehicle perform?
- Which opportunities require towing, bed capacity, cargo space or four-wheel drive?
- Should the vehicle be purchased in cash or financed?
- How much work would be required to cover the payment?
- Which services have the simplest path to the first customer?
- Which opportunities are unrealistic for that vehicle?

## Product direction

The planner simplifies the decision into a visual flow:

**Choose vehicle → understand capabilities → see matching income opportunities → estimate economics → choose a starting path**

Rather than showing every possible variable at once, the interface is intended to progressively reveal the information needed for the next decision.

## Opportunity mapping

Potential opportunities can be mapped to vehicle characteristics, including examples such as:

- junk and debris removal
- furniture and small-item hauling
- local delivery
- landscaping-material transport
- appliance pickup and delivery
- moving assistance
- pressure-washing equipment transport
- mobile service businesses
- trailer-based work when towing capability supports it

The important system behavior is not the list itself. It is the matching logic between the asset and the work the asset can reasonably perform.

## Financial layer

A practical implementation can evaluate:

- vehicle purchase price
- cash vs. financing
- estimated monthly payment
- insurance and fuel assumptions
- job price
- variable job cost
- jobs required to cover fixed vehicle cost
- simple weekly/monthly income scenarios

The planner should present these as understandable estimates rather than false precision.

## UX decision: simplify aggressively

An early version risked becoming too complicated for the intended user.

The direction was changed toward a picture-driven interface with large choices, minimal jargon and clear next actions. That design decision is important: a technically complete system can still fail if the person using it cannot understand what to do next.

## Reusable architecture

The concept can extend beyond pickup trucks.

A reusable implementation could represent each vehicle with structured capability data such as:

- vehicle type
- model year
- bed/cargo dimensions
- payload class
- towing capability
- passenger capacity
- drivetrain
- equipment requirements

Business opportunities can then define their own capability requirements. The system matches the two and explains why an opportunity fits or does not fit.

## What this case study demonstrates

This project demonstrates the ability to translate an open-ended business idea into a usable decision system by combining:

- business-model thinking
- asset/capability matching
- simple financial modeling
- user-centered simplification
- visual product design
- reusable rules instead of one-off recommendations

The main lesson is that useful software does not need to expose all of its complexity. The system can do the reasoning underneath while giving the user a simple next decision.