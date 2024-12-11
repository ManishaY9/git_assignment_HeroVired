# Git Assignment HeroVired

## Project Overview
This repository contains solutions for the HeroVired Git assignment, demonstrating proficiency in Git workflows, feature implementation, and collaborative development.

## Assignments

### 1. CalculatorPlus Application
- **Branch**: `dev`, `feature/sqrt`
- **Functionality**: 
  - Basic arithmetic operations (addition, subtraction, multiplication, division)
  - Square root calculation
- **Key Features**:
  - Error handling for division by zero
  - Implemented square root method

### 2. Git LFS Integration
- **Branch**: `lfs`
- **Functionality**:
  - Integrated Git Large File Storage (LFS)
  - Tracked large binary files over 200MB

### 3. Geometry Calculator
- **Branch**: `geometry-calculator`, `feature/circle-area`, `feature/rectangle-area`
- **Functionality**:
  - Calculate area of a circle
  - Calculate area of a rectangle
- **Git Workflow**:
  - Used Git stash for managing incomplete features
  - Switched between branches seamlessly

## Repository Structure
```
git_assignment_HeroVired/
│
├── CalculatorPlus.py        # CalculatorPlus implementation
├── geometry_calculator.py   # Geometry area calculator
├── large_file.bin           # Large file tracked by Git LFS
└── README.md                # Project documentation
```

## Branches
- `main`: Primary stable branch
- `dev`: Development integration branch
- `feature/sqrt`: Square root feature development
- `lfs`: Git LFS integration
- `geometry-calculator`: Geometry calculator main branch
- `feature/circle-area`: Circle area calculation feature
- `feature/rectangle-area`: Rectangle area calculation feature

## Releases
- `v1.0`: Initial CalculatorPlus implementation
- `v2.0`: Added square root feature and bug fixes

## Git Workflow Demonstrated
- Branch creation and management
- Feature implementation
- Code reviews
- Pull request workflow
- Git stash usage
- Git LFS integration
- Tagging releases

## How to Run
1. Ensure Python 3.x is installed
2. Clone the repository
3. Run individual Python files:
   ```bash
   python CalculatorPlus.py
   python geometry_calculator.py
   ```

