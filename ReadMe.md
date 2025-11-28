# Document AI

Auto-generate architectural documentation and data flow diagrams from Java Spring Boot codebases.

## What it does

Analyzes your Spring Boot application and generates:
- API endpoint documentation
- Data flow diagrams (Mermaid format)
- Sequence diagrams showing endpoint behavior
- Database interaction maps
- Confluence page exports

## Example

Input: Spring Boot project with TransactionController → TransactionService → TransactionRepository

Output:
- Diagram showing complete flow
- Markdown doc with all details
- Confluent page (ready to post)