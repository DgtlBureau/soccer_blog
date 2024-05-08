This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

## Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Инструкция по добавлению поста:

1.  Для загрузки поста необходимо зайти в репозиторий https://github.com/DgtlBureau/soccer_blog, перейти по следующим директориям : src/posts
    ![Инструкция c описанием директории](/public/assets/images/instruction/instruction-1.jpg)

2.                        В разделе posts справа нажать на “Add file”, и выбрать “Upload files” что бы загрузить необходимые файлы с расширением .md . После выбора откроется окно в котором нужно будет нажать на “choose your files” и выбрать файлы. Так же нужно будет поставить отметку на “Commit directly to the main branch.”

    ![Инструкция по добавлению файла](/public/assets/images/instruction/instruction-2.jpg)
    ![Инструкция по загрузке файла](/public/assets/images/instruction/instruction-3.jpg)

3.                        Картинка которая будет использоваться в файле должна лежать в директории public/assets/images/post. В файле который загружается в posts должен быть прописан путь к изображению следующим образом: ‘assets/images/post/<image_name>.png’

    ![Инструкция по загрузке файла](/public/assets/images/instruction/instruction-3_1.jpg)

        ВАЖНО: имя файла картинки не должно содержать пробелы. Вместо пробелов использовать “-” или “\_”

4.                        Файл который загружается в posts должен быть размечен согласно Markdown разметке. Так же необходимо что бы были следующие поля в шапке: title, description, image, date.

    ![Инструкция по заголовкам](/public/assets/images/instruction/instruction-4.jpg)

    ОБРАТИТЕ ВНИМАНИЕ: Заголовки обернуты в специальные символы ("---"). Это необходимо для того что бы получать необходимые данные при считывании md. файла

5.  Для того что-бы поменять фотографию автора, неодходимо поместить или указать (если фото уже имеется в директории) путь нужной фотографии и дописать информацию об авторе: ‘assets/images/author/<image_name>.png/jpg....’
    ![Инструкция по добавлению фото автора](/public/assets/images/instruction/instruction-5.jpg)

6.  Хэштеги которые будут в конце поста необходило обернуть в специальный тег: <font color='#0088cc'>....</font>
    ![Инструкция по добавлению фото автора](/public/assets/images/instruction/instruction-6.jpg)

Инструкция по разметке Markdown файлов есть на следующих источниках: https://gist.github.com/Jekins/2bf2d0638163f1294637,
https://doka.guide/tools/markdown,

В качестве шаблона можно использовать любой пост изменив в нем необходимое содержимое согласно пунктам перечисленных выше!!!

Thu Apr 25 20:15:54 UTC 2024
