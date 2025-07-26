## 1. Creating and Renaming Files/Directories

- **Create a directory**:
  ```bash
    mkdir test_dir
    ```

*Explanation*: Created a folder named `test_dir` inside `/home/labex/project/`.

* **Create a file inside the directory**:

  ```bash
  cd test_dir
  touch example.txt
  ```

  *Explanation*: Moved into `test_dir` and created an empty file named `example.txt`.

* **Rename the file**:

  ```bash
  mv example.txt renamed_example.txt
  ```

  *Explanation*: Renamed the file from `example.txt` to `renamed_example.txt`.

---

## 2. Viewing File Contents

* **View entire content**:

  ```bash
  cat renamed_example.txt
  ```

  *Explanation*: Displayed the content of `renamed_example.txt`.

* **View first 5 lines**:

  ```bash
  head -n 5 renamed_example.txt
  ```

  *Explanation*: Displayed the first 5 lines using `head`.

* **View last 5 lines**:

  ```bash
  tail -n 5 renamed_example.txt
  ```

  *Explanation*: Displayed the last 5 lines using `tail`.

---

## 3. Searching for Patterns

* **Find lines with the word "nibh"**:

  ```bash
  grep 'nibh' renamed_example.txt
  ```

  *Explanation*: Used `grep` to search for the word `nibh` inside `renamed_example.txt`.

---

## 4. Zipping and Unzipping

* **Zip the directory**:

  ```bash
  zip -r test_dir.zip test_dir
  ```

  *Explanation*: Compressed the `test_dir` directory into `test_dir.zip`.

* **Unzip the archive**:

  ```bash
  unzip test_dir.zip
  ```

  *Explanation*: Extracted `test_dir.zip`. Files were extracted in the current directory.

---

## 5. Downloading Files

* **Download a file**:

  ```bash
  wget https://example.com/sample.txt
  ```

  *Explanation*: Attempted to download a sample file, but due to network issues, the command didn’t succeed.

---

## 6. Changing Permissions

* **Create and update permissions**:

  ```bash
  touch secure.txt
  chmod 444 secure.txt
  ls -l secure.txt
  ```

  *Explanation*: Created `secure.txt`, set it to read-only for all users using `chmod 444`.

---

## 7. Working with Environment Variables

* **Set and display an environment variable**:

  ```bash
  export MY_VAR="Hello, Linux\!"
  echo $MY_VAR
  ```

  *Explanation*: Created an environment variable `MY_VAR` with value `"Hello, Linux!"`. Used backslash to escape `!`.

---
