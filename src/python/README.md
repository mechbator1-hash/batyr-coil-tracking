# Python-модули

## Планируемые модули

- `barcode_parser.py` — парсинг штрихкода ММК (28 символов Code128), НЛМК, Северсталь
- `onec_client.py` — REST-клиент для HTTP-сервиса 1С:УТ
- `siemens_reader.py` — чтение счётчика пресса и сварки через python-snap7 (S7-1200/1500) или OPC (S7-300)
- `label_printer.py` — отправка ZPL на TSC DA220W по WiFi
- `main.py` — основной процесс (приёмка / передача в производство)

## Зависимости (предварительно)

```
python-snap7    # Siemens S7-1200/1500
requests        # REST 1С
python-docx     # (опционально, для отчётов)
```
