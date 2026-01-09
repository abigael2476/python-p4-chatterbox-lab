# TODO List - Pass All Tests

## Step 1: Complete the Message Model in `models.py`

- [x] Add `body` column (String)
- [x] Add `username` column (String)
- [x] Add `created_at` column (DateTime, default=datetime.utcnow)
- [x] Add `updated_at` column (DateTime, default=datetime.utcnow)

## Step 2: Implement Routes in `app.py`

- [x] Implement GET /messages - returns all messages ordered by created_at ascending
- [x] Implement POST /messages - creates new message from JSON body
- [x] Implement PATCH /messages/<int:id> - updates message body
- [x] Implement DELETE /messages/<int:id> - deletes message

## Step 3: Run Tests

- [ ] Initialize database and run migrations
- [ ] Run pytest to verify all tests pass
