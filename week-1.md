# კვირა 1 - შესავალი Javascript-ში

## რა არის პროგრამირება?

პროგრამირება არის პროცესი, რომლის დროსაც კომპიუტერს ვაძლებთ გარკვეულ ინსტრუქციებს კონკრეტული პრობლემის გადასაჭრელად.

## ვინ არის პროგრამისტი?

პროგრამისტი არის ადამიანი, რომელიც ქმნის კომპიუტერულ პროგრამებს პროგრამირების ენი გამოყენებით. მათ ასე უწოდებენ Software Developer-ებს ან Software Engineer-ებს.

## რა არის პროგრამირების ენა?

პროგრამირების ენა არის ფორმალური ენა, რომელიც
გამოიყენება კომპიუტერთან კომუნიკაციისთვის. მისი მეშვეობით, პროგრამისტები წერენ ინსტრუქციებს, რომლებსაც კომპიუტერი ასრულებს სხვადასხვა დავალებების შესასრულებლად. პროგრამირების ენებს აქვთ საკუთარი სინტაქსი და წესები, რაც განსაზღვრავს, როგორ უნდა დაიწეროს კოდი და როგორ შეასრულოს ის კომპიუტერმა.

კომპიუტერის ენა არის მხოლოდ 0 და 1, მას მეტი სხვა
არაფერი ესმის, ამიტომ საბოლოო ჯამში პროგრამირების ენით დაწერილი ინსტრუქციები 0-ებსა და 1-ებში გადაითარგმნება.

## რა არის Javascript?

JavaScript არის პროგრამირების ენა, რომელიც გამოიყენება ვებგვერდების დინამიკური და ინტერაქტიული ფუნქციონალის შესაქმნელად. ის ერთ-ერთი ძირითადი ტექნოლოგიაა ვებდეველოპმენტში, HTML-სა და CSS-თან ერთად. JavaScript-ს აქვს უნარი, ბრაუზერში პირდაპირ გაეშვას და ამით იძლევა საშუალებას, რომ ვებგვერდზე დინამიკური ელემენტები, როგორიცაა ანიმაციები, ფორმების შევსება და მათი შემოწმება, რეალურ დროში მონაცემების განახლება და სხვა ინტერაქტიული ფუნქციები, დაინერგოს.

## რაში ვიყენებთ Javascript-ს?

- Front-End Development - საიტის წინა მხარის (იმ ნაწილის ,რომელიც მომხმარებლისთვის ხელშესახებია - დიზაინი, საიტთან ინტერაქცია და ა.შ.) შექნდა. საჭირო რომელიმე ჯავასკრიფტის ბიბლიოთეკის სწავლაც. ჩვენ ვისწავლით ყველაზე პოპულარულ ბიბლიოთეკას - React.js
- Back-End Development - საიტის უკანა მხარის (იმ ნაწილის, რომელსაც მომხმარებელი ვერ ხედავს - დატაბაზები, მონაცემების Front-თან გაგზავნა, გადახდის სისტემები და ა.შ.). ბექენდ აპლიკაციების შექმნა შეიძლება node.js-ის გამოყენებით, სადაც კოდი იწერება ჯავასკრიფტის ენაზე.
- Full Stack Development - Front-End & Back-End
- Native Mobile Applications - ისეთი აპლიკაციების შექმნა, რომელიც IOS-ზეც გაეშვება და Android-ზეც. ამას შევძლებთ React Native-ის გამოყენებით
- Desktop Applications - დესკტოპ აპლიკაციების შექმნა - Electron
- Game Development - თამაშების შექმნაც შეგვიძლია, მაგრამ ამ სფეროში მაინც C++ და C# ლიდერობენ.

## სად ვწეროთ კოდი?

1. Visual Studio Code-ში დავწეროთ კოდი და node-ის გარემოში გავუშვათ
2. ონლაინ კომპილატორი გამოვიყენოთ, მაგალითად [PlayCode](https://playcode.io)

## მნიშვნელობები

კომპიუტერის მეხსიერებაში ინფორმაციის შესანახ პატარა
ნაწილაკებს (chunk-ებს) მნიშვნელობები ეწოდებათ. გვაქვს რამდენიმე ტიპის მნიშვნელობები, მაგალითად: string (ტექსტური), number (რიცხვითი), boolean (true ან false)

## number

შეგვიძლია ჩავწეროთ ნებისმიერი სახის რიცხვი, მაგალითად: 5, -5, 4.23, 2.99e8. მათემატიკური ოპერატორების გამოყენებაც იგივე წესით ხორციელდება, როგორც მათემატიკაში.

## Expression - გამოსახულება

ისეთ ჩანაწერს, რომელიც რაიმე ტიპის მნიშვნელობას
აბრუნებს, expression ანუ გამოსახულება ეწოდება.

## წერტილ-მძიმე (;)

ჯავასკრიფტში ყველა ინსტრუქციის ბოლოს ვწერთ წერტილ-მძიმეს. აუცილებელი არაა, მაგრამ კარგი პრაქტიკაა.

## console.log() ფუქნცია

ვიყენებთ მნიშვნელობების ეკრანზე(კონსოლსა ან ტერმინალში) გამოსატანად

## string

არსებობს სტრინგის ჩაწერის სამი გზა: ორმაგი ბრჭყალებით, ერთმაგი ბრჭყალებით, ბექთიქებით(backtick) (``). რითიც გავხსნით სტრინგს, იმავე ბრჭყალით უნდა დავხუროთ

- ორმაგ ბრჭყალებში სხვა ორმაგი ბრჭყალის ჩაწერა არ შეიძლება - პოგრამას ჰგონია, რომ სტრინგი მთავრდება. ამის დასაფიქსად შეგვიძლია escape character-ის (\ - ბექსლეშის) გამოყენება.
- ერთმაგ ბრჭალებში შეიძლება ორმაგი ბრჭყალის გამოყენება, რადგან სხვა ტიპის ბრჭყალია შიგნით და პროგრამას არ ჰგონია, რომ სტრინგი იხურება.
- ბექთიქები - ასეთ სტრინგებს ასევე ვუწოდებთ template string-ებს ან template literal-ს - გამოიყენება სტრინგის მნიშვნელობის გამოსატანად, მაგალითად:

```js
`მე ვარ ${10 + 9} წლის`;
```

## ცვლადები

ცვლადი გამოიყენება ნებისმიერი ტიპის მნიშვნელობის
შესანახად. ჯერ ვწერთ ცვლადის შესაქმნელ keyword-ს - let. შემდგომ იწერება ცვლადის სახელი, მერე მინიჭების ოპერატორი(=) და ბოლოს ის მნიშვნელობა, რომელიც გვინდა რომ ცვლადში შევინახოთ. მაგალითად:

```js
let x = 10;
```

ცვლადის მნიშვნელობის შესაცვლელად ანუ სხვა მნიშვნელობის მისთვის მისანიჭებლად ვიყენებთ ისევ მინიჭების ოპერატორს (=):

```js
x = 5;
```

## prompt() ფუქნცია

გამოიყენება მომხმარებლისთვის კითხვის დასასმელად. შემოყვანილი მნიშვნელობა ყოველთვის ინახება string ტიპის მნიშვნელობად.

## Number() ფუნქცია

გამოიყენება string ტიპის მნიშვნელობის number ტიპის მნიშვნელობაში გადასაყვანად.