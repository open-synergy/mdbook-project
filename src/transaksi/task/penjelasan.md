# Penjelasan

## <a name="bagian-header">A. BAGIAN HEADER</a>

![](../../img/task/penjelasan-header.png)

#### <a name="field-name">Task Summary</a>

Penjelasan singkat *task*

#### <a name="field-template">Template</a>

Template task yang digunakan

#### <a name="field-category">Category</a>

Kategori task

#### <a name="field-project">Project</a>

Project yang memiliki task tersebut

#### <a name="field-assigned">Assigned To</a>

User yang ditugaskan untuk menyelesaikan task

#### <a name="field-reviwer">Reviewer</a>

User yang ditugaskan untuk mereview penyelesaian task

#### <a name="field-deadline">Deadline</a>

Abaikan

#### <a name="field-tags">Tags</a>

Penggolongan task

## <a name="tab-descrption">B. TAB DESCRIPTION</a>

![](../../img/task/penjelasan-tab-description.png)

#### <a name="field-description">Description</a>

Penjelasan task

### <a name="tabel-timesheet">B.1. Tabel Timesheet</a>

#### <a name="field-timesheet-description">Description</a>

Deskripsi timesheet

#### <a name="field-timesheet-quantity">Quantity</a>

Jumlah jam yang digunakan (format HH:MM)

#### <a name="field-timesheet-date">Date</a>

Tanggal timesheet dilakukan

#### <a name="field-timesheet-invoiceable">Invoiceable</a>

#TODO

## <a name="tab-extra-info">C. TAB EXTRA INFO</a>

![](../../img/task/penjelasan-tab-other-info.png)

#### <a name="field-priority">Priority</a>

Prioritas task

#### <a name="field-customer">Customer</a>

Abaikan

#### <a name="field-order-line">Order Line</a>

Abaikan

#### <a name="field-sequence">Sequence</a>

Urutan task

#### <a name="field-state">State</a>

Status dari task

#### <a name="field-company">Company</a>

Pemilik task

#### <a name="field-last-stage-update">Last Stage Update</a>

Waktu terakhir task berubah stage

## <a name="tab-schedule">D. TAB SCHEDULE</a>

![](../../img/task/penjelasan-tab-schedule.png)

#### <a name="field-timezone">Timezone</a>

Zona waktu yang digunakan dalam menghitung jadwal

#### <a name="field-start-schedule-based-on">Start Schedule Based On</a>

Patokan tanggal mulai task. Beberapa opsi dapat yang dapat dipilih:

* **Manual**. User harus secara manual menentukan tanggal mulai task
* **Task Baseline Start**. Tanggal mulai akan dihitung dengan berpatokan pada **Baseline Start** yang dimiliki oleh task yang dipilih pada isian **Task Based Schedule**
* **Task Baseline Finish**. Tanggal mulai akan dihitung dengan berpatokan pada **Baseline Finish** yang dimiliki oleh task yang dipilih pada isian **Task Based Schedule**
* **Project Baseline Start**. Tanggal mulai akan dihitung dengan berpatokan pada **Baseline Start** yang dimiliki oleh project yang dipilih pada isian **Project Based Schedule**
* **Project Baseline Finish**. Tanggal mulai akan dihitung dengan berpatokan pada **Baseline Finish** yang dimiliki oleh project yang dipilih pada isian **Project Based Schedule**

#### <a name="field-project-based-schedule-start">Project Based Schedule</a>

*Project* yang akan digunakan sebagai patokan untuk menentukan tanggal mulai task. Hanya muncul apabila isian **Start Schedule Based On** tidak sama dengan **Manual**

#### <a name="field-task-based-schedule-start">Task Based Schedule</a>

*Task* yang akan digunakan sebagai patokan untuk menentukan tanggal mulai *project*. Hanya muncul apabila isian **Start Schedule Based On** tidak sama dengan **Manual**

#### <a name="field-baseline-start-offset">Baseline Start Offset</a>

Perhitungan penambahan/pengurangan tanggal mulai

#### <a name="field-baseline-start-offset-uom">Baseline Start Offset UoM</a>

Satuan perhitungan penambahan/pengurangan tanggal mulai

#### <a name="field-finish-schedule-based-on">Finish Schedule Based On</a>

Patokan tanggal selesai task. Beberapa opsi dapat yang dapat dipilih:

* **Manual**. User harus secara manual menentukan tanggal selesai project
* **Task Baseline Start**. Tanggal selesai akan dihitung dengan berpatokan pada **Baseline Start** yang dimiliki oleh *task* yang dipilih pada isian **Task Based Schedule**
* **Task Baseline Finish**. Tanggal selesai akan dihitung dengan berpatokan pada **Baseline Finish** yang dimiliki oleh *task* yang dipilih pada isian **Task Based Schedule**
* **Project Baseline Start**. Tanggal selesai akan dihitung dengan berpatokan pada **Baseline Start** yang dimiliki oleh *project* yang dipilih pada isian **Project Based Schedule**
* **Project Baseline Finish**. Tanggal selesai akan dihitung dengan berpatokan pada **Baseline Finish** yang dimiliki oleh *project* yang dipilih pada isian **Project Based Schedule**

#### <a name="field-project-based-schedule-finish">Project Based Schedule</a>

*Project* yang akan digunakan sebagai patokan untuk menentukan tanggal selesai task. Hanya muncul apabila isian **Finish Schedule Based On** tidak sama dengan **Manual**

#### <a name="field-task-based-schedule-finish">Task Based Schedule</a>

*Task* yang akan digunakan sebagai patokan untuk menentukan tanggal selesai *project*. Hanya muncul apabila isian **Finish Schedule Based On** tidak sama dengan **Manual**

#### <a name="field-baseline-finish-offset">Baseline Finish Offset</a>

Perhitungan penambahan/pengurangan tanggal selesai

#### <a name="field-baseline-finish-offset-uom">Baseline Finish Offset UoM</a>

Satuan perhitungan penambahan/pengurangan tanggal selesai

## <a name="tab-schedule">E. TAB DEPENDENCIES</a>

![](../../img/task/penjelasan-tab-dependency.png)

### <a name="tabel-predecessor">E.1 TABEL PREDECESSOR</a>

#### <a name="field-predecessor-task">Predecessor Task</a>

Task pendahulu

#### <a name="field-predecessor-dependency-type">Dependency Type</a>

Jenis hubungan dengan predecessor. Terdapat beberapa jenis hubungan yang dapat dipilih:

* **Start-To-Finish**. Predecessor harus dimulai terlebih dahulu sebelum task dapat diselesaikan.
* **Start-To-Start**. Predecessor harus dimulai terlebih dahulu sebelum task dapat dimulai.
* **Finish-To-Start**. Predecessor harus diselesaikan terlebih dahulu sebelum task dapat dimulai.
* **Finish-To-Finish**. Predecessor harus diselesaikan terlebih dahulu sebelum task dapat diselesaikan.

#### <a name="field-predecessor-task-stage">Task Stage</a>

#### <a name="field-predecessor-task-state">Task State</a>

### <a name="tabel-successor">E.1 TABEL SUCESSOR</a>

#### <a name="field-successor-task">Successor Task</a>

#### <a name="field-successor-dependency-type">Dependency Type</a>

#### <a name="field-successor-task-stage">Task Stage</a>

#### <a name="field-successor-task-state">Task State</a>

## <a name="tab-schedule">F. TAB QUALITY CONTROL</a>

![](../../img/task/penjelasan-tab-qc.png)

#### <a name="field-qc-pass">QC Passed?</a>

### <a name="tabel-qc">F.1 TABEL QUALITY CONTROL</a>

#### <a name="field-qc-question">Question</a>

#### <a name="field-qc-type">Type</a>

#### <a name="field-qc-qualitative-value">Qualitative Value</a>

#### <a name="field-qc-quantitative-value">Quantitative Value</a>

#### <a name="field-qc-valid-value">Valid Value</a>

#### <a name="field-qc-success">Success?</a>

## <a name="tab-instruction">G. TAB INSTRUCTION</a>

![](../../img/task/penjelasan-tab-instruction.png)

### <a name="tabel-instruction">G.1 TABEL INSTRUCTION</a>

#### <a name="field-instruction">Instruction</a>

#### <a name="field-instruction-url">Instruction URL</a>
