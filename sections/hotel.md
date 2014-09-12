Hotel
=====


Get Hotel info
--------------

* `GET /show/{hotel_id}` will return the specified hotel.

```json
{
  hotel_id: "7928",
  hotel_name: "منتجع جولدن توليب خليج الدانة",
  stars: "4",
  description: "إذا كنت في حاجة إلى زيارة المنطقة الشرقية من المملكة العربية السعودية، فهناك الكثير من الفنادق التي يمكنك الاختيار من بينها بما في ذلك منتجع جولدن توليب دانا باي في منطقة نصف القمر الواقع على بعد حوالي 50 كيلومترا من مدينة الخبر. قربها من الشاطئ، ويوفر فرص مثل الرياضات المائية مالتزلج على الماء، وركوب قارب الموز، ونقلات الغوص. هناك أيضا خيار أخذ صورة فوتوغرافية تحت الماء في المنتجع. مطعم دولفين في المنتجع يقدم للنزلاء وجبات لذيذة مقدمة من المطابخ الدولية والسعودية والشرقية. خليج مقهى داينر هو الخيار الأفضل لتناول وجبة خفيفة سريعة. مقهى أمواج هو أيضا خيارجيد لتناول القهوة والمشروبات المنعشة. بالاضافة الى مارينا بلازا الذييجب تجربة البوظة فيه. بالنسبة لأولئك الذين يفضلون الاسترخاء، فهناك مرافق السبا بما في ذلك ساونا وحمام بخار للسيدات والسادة. كما يمكن للوالدين الاعتماد على مركز الرعاية النهارية للأطفالأثناء ذلك. وإذا كنت تفضل اشراك الجميع في الأسرة، فهناك مرافق لعب داخلية وخارجية للجميع. ويوفر المنتجع فيلات بغرفة نوم واحدة وبرك سباحة خاصة. غير أن الشرفات توفر منظر جميل " لجولدن بيتش" الخاص وخليج دانا لاغون. المنتجع للعائلات فقط.. يرجى ملاحظة أنه وفقاً للقانون السعودي يلزم أن تكون العائلات برفقة (محرم) في جميع منتجعات المملكة العربية السعودية وذلك مثل الزوج أو الأب أو الأخ أو العم أو الابن مع قيامهم بحمل بطافة هوية. ",
  lat: "26.267143080777",
  lon: "50.21584510803223",
  city_id: "180543",
  city_name: "الخُبر",
  currancy: "SAR",
  images: [
    {
      id: "2472",
      url: "/app/yamsafer/images/system/tmp/Sala1A.jpg",
      hotel_id: "7928",
      thumb_large: "/app/yamsafer/images/system/tmp/large_Sala1A.jpg",
      thumb_medium: "/app/yamsafer/images/system/tmp/medium_Sala1A.jpg",
      thumb_small: "/app/yamsafer/images/system/tmp/small_Sala1A.jpg"
    },
    {
      id: "2471",
      url: "/app/yamsafer/images/system/tmp/RENOVATE-1.jpg",
      hotel_id: "7928",
      thumb_large: "/app/yamsafer/images/system/tmp/large_RENOVATE-1.jpg",
      thumb_medium: "/app/yamsafer/images/system/tmp/medium_RENOVATE-1.jpg",
      thumb_small: "/app/yamsafer/images/system/tmp/small_RENOVATE-1.jpg"
    },
    {
      id: "8966",
      url: "/app/yamsafer/images/system/tmp/9edited(1).jpg",
      hotel_id: "7928",
      thumb_large: "/app/yamsafer/images/system/tmp/large_9edited(1).jpg",
      thumb_medium: "/app/yamsafer/images/system/tmp/medium_9edited(1).jpg",
      thumb_small: "/app/yamsafer/images/system/tmp/small_9edited(1).jpg"
    }
  ],
  rooms: [
    {
      room_id: "10786",
      name: "فيلا ماهر مع الباحة ",
      base_rate: 339.0384,
      promotion_rate: 260.4208,
      has_promotion: true,
      availability: "3"
    },
    {
      room_id: "10788",
      name: "فيلا شراع ",
      base_rate: 595.4336,
      promotion_rate: 355.1408,
      has_promotion: true,
      availability: "2"
    },
  ],
  availability: true
}
```

All rates are in USD.