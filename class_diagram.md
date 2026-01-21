# Sticky Notes Application - Class Diagram

## Note Class

### Attributes
- `id`: Integer (Primary Key, Auto-generated)
- `title`: CharField (max_length=200)
- `content`: TextField
- `created_at`: DateTimeField (auto_now_add=True)
- `updated_at`: DateTimeField (auto_now=True)

### Methods
- `__str__()`: Returns the title of the note

### Relationships
- None (Standalone model)