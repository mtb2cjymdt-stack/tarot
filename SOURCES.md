# Источники и редакционные принципы

Основной исторический источник: Arthur Edward Waite, *The Pictorial Key to the Tarot* (1911), с иллюстрациями Pamela Colman Smith.

- Полная книга: https://sacred-texts.com/book/the-pictorial-key-to-the-tarot
- Символика старших арканов: часть II, раздел 2.
- Описания младших арканов: часть III, раздел 2.
- Прямые и перевёрнутые значения старших арканов: часть III, раздел 3.
- Дополнительные значения младших арканов: часть III, раздел 4.
- Искусство чтения расклада: часть III, раздел 6.

`readings.js` содержит оригинальные краткие русские пересказы исторических мотивов. Это не полный перевод книги и не воспроизведение всех противоречивых предсказательных формулировок Уэйта. Болезни, смерть и подозрения не подаются как установленные факты о посетителе или третьих лицах. Расовая, гендерная и социальная характеристика придворных карт не воспроизводится.

Современные вопросы для размышления, применение к отношениям и работе, связки карт в `app.js` — авторская интерпретация. Алгоритм сочетаний учитывает только открытые карты, их ориентацию, масть, порядок и позиции выбранного расклада. Для нескольких пар написаны отдельные связки; прочие строятся по общим тематическим правилам. Это не ИИ, не универсальный словарь всех возможных сочетаний и не точное предсказание.

Символические описания относятся к классическим изображениям Уэйта—Смит, а не к каждой детали стилизованного рисунка с миньоном. У Силы номер VIII, у Справедливости XI, как в системе Уэйта—Смит; внутренние идентификаторы сцен сохранены.

## Lectures longues (version locale)

`essays.js` ajoute 78 commentaires originaux en russe, chacun avec un développement, un exemple, une réserve et une question. La Six de Swords / Шестёрка Мечей dispose d'un développement supplémentaire par domaine. Les recommandations contemporaines ne sont pas présentées comme des citations de Waite.

Organisation éditoriale comparée aux guides des éditeurs :
- Labyrinthos, Six of Swords : https://labyrinthos.co/blogs/tarot-card-meanings-list/six-of-swords-meaning-tarot-card-meanings
- Biddy Tarot, Six of Swords : https://biddytarot.com/tarot-card-meanings/minor-arcana/suit-of-swords/six-of-swords/

Ces guides ont servi à examiner la structure de lecture (description, sens, domaines, position inversée). Leurs textes ne sont pas reproduits. La différence entre les mots-clés historiques de Waite et les inversions modernes est explicitée dans la fiche de la Шестёрка Мечей.

## Séparation visible des sources

Chaque entrée possède maintenant `historical.upright`, `historical.reversed` et `historical.source`. Le bloc « Значение по Уэйту » affiche une sélection courte de significations historiques traduites en russe, explicitement non exhaustive et non présentée comme citation littérale. Les paragraphes éditoriaux antérieurs ne sont pas renommés en contenu historique : ils restent dans « Дополнительные размышления ».

Les descriptions personnelles, exemples, conseils, questions, lectures par domaine et combinaisons sont modernes. Les aperçus de tirage et le prompt ChatGPT reprennent cette distinction. Certaines formulations anciennes sont dures ou contradictoires ; elles sont signalées comme vocabulaire historique, jamais comme diagnostic ou fait établi sur le visiteur. Pour la Deux de Coupes, l'absence de liste inversée dans la description principale et l'apport du supplément sont signalés.
