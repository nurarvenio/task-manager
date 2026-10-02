# TaskTracker

**TaskTracker**, C# Windows Forms kullanılarak geliştirilmiş pratik ve dinamik bir görev takip uygulamasıdır.

## 🚀 Özellikler

- **Görev Ekleme (`Add Item`):** `TextBox` alanına yazılan görevleri ana yapılacaklar listesine (`CheckedListBox`) ekler ve giriş alanını temizler.
- **Görev Silme (`Delete`):** Ana listede seçili olan görevi listeden kaldırır.
- **Otomatik Tamamlama Transferi:** Ana listede bir görevin kutucuğu işaretlendiğinde (`ItemCheck`), görev otomatik olarak **Completed Tasks List** (`listBoxCompleted`) alanına taşınır ve thread-safe (`BeginInvoke`) yapısıyla ana listeden silinir.
- **Tamamlananları Temizleme (`Del`):** Tamamlanan görevler listesini tek tıkla tamamen temizler.

## 🛠️ Kullanılan Teknolojiler & Bileşenler

- **Dil:** C#
- **Platform:** .NET Framework / Windows Forms
- **Arayüz Elemanları:** `CheckedListBox`, `ListBox`, `TextBox`, `Button`, `Panel`, `Label`

## 💻 Kullanım / Ekran Düzeni

- **Add Task Paneli:** Yeni görev metni girilip "Add Item" butonuna basılır. "Delete" butonu ile listeden seçilen öğeler silinebilir.
- **Tasks List Paneli:** Aktif görevlerin listelendiği işaretlenebilir alan.
- **Completed Tasks List Paneli:** Tamamlanan görevlerin aktarıldığı ve "Del" butonu ile temizlenebildiği alan.




---

# TaskTracker (English)

**TaskTracker** is a simple and dynamic task management application developed with C# Windows Forms.

## 🚀 Features

- **Add Task (`Add Item`):** Adds tasks entered into the `TextBox` to the main task list (`CheckedListBox`) and clears the input field.
- **Delete Task (`Delete`):** Removes the currently selected task from the main list.
- **Automatic Completion Transfer:** When a task is checked (`ItemCheck`) in the main list, it automatically moves to the **Completed Tasks List** (`listBoxCompleted`) and gets safely removed from the main list using a thread-safe `BeginInvoke` mechanism.
- **Clear Completed (`Del`):** Clears all items in the completed tasks list with a single click.

## 🛠️ Technologies & Components Used

- **Language:** C#
- **Platform:** .NET Framework / Windows Forms
- **UI Components:** `CheckedListBox`, `ListBox`, `TextBox`, `Button`, `Panel`, `Label`

## 💻 Layout & Usage

- **Add Task Panel:** Enter new task text and click "Add Item". Selected items can also be deleted using the "Delete" button.
- **Tasks List Panel:** Checkable list area showing active tasks.
- **Completed Tasks List Panel:** Area where completed tasks are stored and can be cleared with the "Del" button.
