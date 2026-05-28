# Campus Bus Route & Seat Allocation System

## Overview

This is a console-based application that simulates how a university manages its campus transport service. The system handles bus routes, vehicle assignments, and student seat allocations using only static arrays, C-style strings, and fundamental programming constructs.

## Features

- **Route Management** – Maintains a fixed set of bus routes with assigned vehicles
- **Seat Allocation** – Registers students to routes and assigns available seats
- **Update Records** – Modify existing allocations when needed
- **Cancel Allocations** – Remove student bookings and free up seats
- **Search Functionality** – Find records by student ID or route number
- **Conflict Detection** – Automatically detects:
  - Overbooking (exceeding bus capacity)
  - Duplicate student allocations
  - Invalid route or bus references
- **Summary Reports** – Generate administrative reports for transport management

## Technical Constraints

This project was built using only:
- Static arrays (no dynamic memory allocation)
- Character arrays (`char[]`) instead of C++ strings
- Loops and nested loops
- If/else logic
- No external libraries or advanced data structures

## Interface

The program is fully menu-driven, providing an interactive console experience for transport administrators.

## Purpose

This project demonstrates fundamental C++ programming skills including array manipulation, input validation, conflict resolution, and report generation without relying on object-oriented features or the STL.
