# Engima 2017 Notes

## Behaviors and Detection

### StreamAlert: A Serverless, Real-time Intrusion Detection Engine

- Low cost
- Role based Access Control - AWS IAM
- _

#### Writing Rules
- User defined function that evaluates to false/true
- Rule looks like this:
```python
@rule('invalid_user, ...)
   def invalid_user (rec):
     return true
```