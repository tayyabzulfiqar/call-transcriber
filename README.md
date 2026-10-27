# Call Transcriber

Bulk-transcribe call-center recordings and get a clean Excel sheet back.

I built this for my operations team at FezCommunication and used it on real call recordings.

## What it does

- Upload many audio files at once.
- Transcribe them with Deepgram, with speaker labels (who is talking) and punctuation.
- Pull out names, phone numbers, emails, companies, payments and commitments.
- Guess the call type and score each speaker's sentiment.
- Export everything to Excel in a fixed column order.

## Stack

Python, Streamlit, Deepgram API, pandas, XlsxWriter

## Run

```bash
pip install -r Requirements.txt
streamlit run app.py
```

Paste your Deepgram API key in the sidebar. The key is never stored.
