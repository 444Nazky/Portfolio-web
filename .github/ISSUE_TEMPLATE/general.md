name: Tugas / Pertanyaan Umum
description: Gunakan template ini untuk pekerjaan atau pertanyaan umum.
title: "[Task] "
labels: [enhancement]
body:
  - type: markdown
    attributes:
      value: |
        Terima kasih sudah meluangkan waktu untuk mengisi form ini.
  - type: textarea
    id: what
    attributes:
      label: Apa yang ingin ditambahkan atau diubah?
      description: Jelaskan tugas/permintaan secara singkat dan jelas.
    validations:
      required: true
  - type: textarea
    id: why
    attributes:
      label: Kenapa ini diperlukan?
    validations:
      required: false
  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance criteria
      description: Apa yang harus benar setelah pekerjaan ini selesai?
    validations:
      required: true
  - type: textarea
    id: additional
    attributes:
      label: Additional context
    validations:
      required: false


