name: Course Assignment
description: Assign a learning course or learning path to a contributor
title: "[COURSE] "
labels:
  - course
  - training
body:
  - type: input
    id: contributor_name
    attributes:
      label: Contributor Name
      description: Name of the contributor
      placeholder: "Anand G"
    validations:
      required: true

  - type: dropdown
    id: contributor_role
    attributes:
      label: Contributor Role
      options:
        - Trainee Engineer
        - Associate Contributor
        - Project Contributor
        - Technical Lead Intern
        - Research Scholar
        - Open Source Contributor
        - Other
    validations:
      required: true

  - type: input
    id: mentor_name
    attributes:
      label: Assigned Mentor
      placeholder: "John Doe"
    validations:
      required: true

  - type: input
    id: course_id
    attributes:
      label: Course ID
      description: Reference the Course ID from the Course Catalog
      placeholder: "GIT-001"
    validations:
      required: true

  - type: input
    id: course_name
    attributes:
      label: Course Name
      placeholder: "Git Fundamentals"
    validations:
      required: true

  - type: input
    id: learning_path
    attributes:
      label: Learning Path
      description: Foundation, Research, AI Agent, FaaS, DevOps, etc.
      placeholder: "Foundation"

  - type: input
    id: course_repository
    attributes:
      label: Course Repository
      description: Repository containing the learning materials
      placeholder: "bit-guidances/courses"

  - type: textarea
    id: objective
    attributes:
      label: Learning Objective
      description: What should the contributor learn?
      placeholder: |
        Learn Git fundamentals including branching,
        committing, merging and Pull Request workflow.
    validations:
      required: true

  - type: textarea
    id: prerequisites
    attributes:
      label: Prerequisites
      placeholder: |
        - Git installed
        - GitHub account created

  - type: textarea
    id: deliverables
    attributes:
      label: Expected Deliverables
      placeholder: |
        - Course completed
        - Assignment completed
        - Pull Request submitted
        - Questions answered
    validations:
      required: true

  - type: input
    id: due_date
    attributes:
      label: Due Date
      placeholder: "YYYY-MM-DD"

  - type: checkboxes
    id: completion
    attributes:
      label: Completion Checklist
      options:
        - label: Course enrolled
        - label: All lessons completed
        - label: Course assignment completed
        - label: Practical exercise completed
        - label: Pull Request submitted (if applicable)
        - label: Documentation updated
        - label: Mentor discussion completed
        - label: Mentor approved

  - type: textarea
    id: evidence
    attributes:
      label: Completion Evidence
      description: Add certificate link, screenshots, assignment PR, or repository links
      placeholder: |
        Certificate:
        Pull Request:
        Assignment Repository:
        Screenshots:

  - type: dropdown
    id: status
    attributes:
      label: Current Status
      options:
        - Assigned
        - In Progress
        - Waiting for Review
        - Completed
        - Needs Improvement
    validations:
      required: true

  - type: textarea
    id: mentor_feedback
    attributes:
      label: Mentor Feedback
      description: To be completed by the mentor after review
      placeholder: |
        Strengths:
        Improvements:
        Recommendation:

  - type: checkboxes
    id: final_checklist
    attributes:
      label: Final Approval
      options:
        - label: Course requirements verified
        - label: Practical skills demonstrated
        - label: Assignment accepted
        - label: Course marked as completed
