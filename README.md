### Rust Chat Server - Run Instructions
** 1. Clone the repository
```markdown
git clone <repo-url>
cd rust-chat-server
```
** 2. Create the SQLite database
```markdown
sqlite3 chat.db < chat_database.sql
```

** 3. Build the server (release mode)
```markdown
cargo build --release --bin server
```
** 4. Run the server
```markdown 
./target/release/server
```
