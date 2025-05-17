import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function HomePage() {
  return (
    <main className="min-h-screen bg-white text-gray-900">
      <header className="bg-[#004d40] text-white p-4 shadow-md">
        <h1 className="text-2xl font-bold">Түмэн Говь Сүжөү ХХК</h1>
        <nav className="mt-2 flex gap-6 text-sm">
          <a href="#about" className="hover:underline">Бидний тухай</a>
          <a href="#operations" className="hover:underline">Үйл ажиллагаа</a>
          <a href="#goals" className="hover:underline">Зорилго</a>
          <a href="#contact" className="hover:underline">Холбоо барих</a>
        </nav>
      </header>

      <section className="p-6 text-center bg-gray-50">
        <h2 className="text-3xl font-semibold mb-2">Жишиг уурхайн жишиг сайт</h2>
        <p>Монгол Улсаас БНХАУ руу нүүрс экспортлогч уул уурхайн компани</p>
      </section>

      <section id="about" className="p-6">
        <h3 className="text-xl font-semibold mb-2">Компанийн товч танилцуулга</h3>
        <p>
          "Түмэн Говь Сүжөү" ХХК нь Монгол Улс, Дорноговь аймгийн Мандах сумын Алаг Цав ордын 4-р ашиглалтын талбайд 2025 онд үүсгэн байгуулагдаж, үйл ажиллагаагаа эхлүүлсэн. 
          Манай компани нь нүүрс олборлолт, экспортын чиглэлээр үйл ажиллагаа явуулдаг бөгөөд нүүрсийг Хангийн боомтоор дамжуулан БНХАУ-д экспортлодог.
        </p>
      </section>

      <section id="operations" className="p-6 bg-gray-100">
        <h3 className="text-xl font-semibold mb-4">Үйл ажиллагааны статистик</h3>
        <ul className="list-disc list-inside">
          <li>Нийт 3,200,000 м³ хөрс хуулалт хийсэн</li>
          <li>279,550 тн нүүрс олборлосон</li>
          <li>250,000 тн нүүрсийг Хангийн боомтод байрлуулсан</li>
          <li>10,000,000 тн нүүрсний баталгаат нөөцтэй</li>
          <li>Жилд дунджаар 2,000,000 тн нүүрс олборлох зорилготой</li>
          <li>Ажиллах хүч: 111 монгол, 21 гадаад ажилтан</li>
        </ul>
      </section>

      <section id="goals" className="p-6">
        <h3 className="text-xl font-semibold mb-2">Зорилго</h3>
        <p>
          Манай компани уул уурхайн салбарт жишиг уурхай болж хөгжих, 
          экспортын чанартай бүтээгдэхүүн үйлдвэрлэх, олон улсын стандартыг ханган ажиллахыг зорьж байна.
        </p>
      </section>

      <section id="contact" className="p-6 bg-gray-100">
        <h3 className="text-xl font-semibold mb-4">Холбоо барих</h3>
        <p>Хаяг: Монгол Улс, Дорноговь аймаг, Мандах сум, 2-р баг, Алаг Цав орд</p>
        <p>И-мэйл: info@tumengobi.mn (жишээ)</p>
        <p>Утас: +976-xxxxxxx</p>
      </section>

      <footer className="text-center p-4 text-sm text-gray-600">
        © 2025 Түмэн Говь Сүжөү ХХК. Бүх эрх хуулиар хамгаалагдсан.
      </footer>
    </main>
  );
} 
