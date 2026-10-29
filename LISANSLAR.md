# Lisanslar ve atıflar

Baş-Boyun Anatomi Atlası, lisansları farklı parçalardan oluşan bir derlemedir. Her parça kendi lisansıyla kullanılabilir. Bir parçayı kullanırken o parçanın lisansına uyun ve aşağıdaki atıfları koruyun.

## 1. Atlasın kendi içeriği

**Yapı kartları, "Kısaca" özetleri ve arayüz metinleri**
© 2026 Mert Ocak. [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.tr) lisansıyla paylaşılır.
Metinler yapay zekâ desteğiyle (Claude, Anthropic) yazılmış ve gözden geçirilmiştir. Türkçe terimler ve bilgiler, başvuru kaynaklarının yanında şu ders kitabıyla karşılaştırılmıştır: Arifoğlu Y. *Her Yönüyle Anatomi*. 3. baskı. İstanbul: İstanbul Tıp Kitabevleri. Kitaptan metin alınmamıştır.

**Sayfanın kodu (index.html içindeki HTML, CSS ve JavaScript)**
© 2026 Mert Ocak. MIT lisansı; metni [LICENSE](LICENSE) dosyasındadır.

## 2. Model atlası

- **Z-Anatomy** — Gauthier Kervyn ve ark., [Models of human anatomy](https://github.com/Z-Anatomy/Models-of-human-anatomy). [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- **BodyParts3D** — © The Database Center for Life Science. [CC BY-SA 2.1 Japonya](https://creativecommons.org/licenses/by-sa/2.1/jp/deed.en). Z-Anatomy modelleri BodyParts3D'den türetilmiştir.

Değişiklikler: yapılar baş-boyun bölgesine göre seçilmiş, sinir ve damarlar merkez çizgileri üzerinde şematik tüplerle yeniden oluşturulmuş, yüzeyler sıkıştırılmış ve 1 mm'lik etiket hacmine dönüştürülerek kesit plakaları üretilmiştir. Türetilen dosyalar (`models/atlas_*.glb`, `model/lab_*.png`) CC BY-SA 4.0 lisanslıdır.

## 3. MR kesitleri

- **IXI veri seti** — [brain-development.org/ixi-dataset](https://brain-development.org/ixi-dataset/), katılımcı IXI075 (Guy's Hastanesi, Londra; 1,5 T), T1 ve T2 ağırlıklı seriler. [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

Değişiklikler: yoğunluk düzeltmesi (N4), ANTs ile modele kayıt, 1 mm'lik ızgaraya yeniden örnekleme, 8 bit ve kayıplı sıkıştırma. Türetilen görüntüler (`model/mr*.webp`) CC BY-SA 3.0 lisanslıdır.

## 4. CBCT vakası — yalnızca ticari olmayan kullanım

- **ToothFairy3 veri seti** — AImageLab, Modena ve Reggio Emilia Üniversitesi, [ditto.ing.unimore.it/toothfairy3](https://ditto.ing.unimore.it/toothfairy3), vaka F_008. [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Değişiklikler: görüntü yaklaşık 115 × 96 × 79 mm'lik bir alanda kırpılmış, 8 bit ve kayıplı sıkıştırılmış; 3B yüzeyler etiketlerden üretilmiştir. Türetilen dosyalar (`cbct/`, `models/cbct_*.glb`) CC BY-NC-SA 4.0 lisanslıdır ve ticari amaçla kullanılamaz.

Veri setini sağlayan ekip, bu veriyi kullanan yayınların ToothFairy3 yarışmasına ve şu çalışmalara atıf yapmasını istemektedir:

1. Bolelli F, Lumetti L, van Nistelrooij N, ve ark. Multi-structure segmentation in CBCT volumes: The ToothFairy2 challenge. *Medical Image Analysis*. 2026;104095. doi:10.1016/j.media.2026.104095
2. Bolelli F, Marchesini K, van Nistelrooij N, Lumetti L, Pipoli V, Ficarra E, Vinayahalingam S, Grana C. Segmenting Maxillofacial Structures in CBCT Volumes. *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*. 2025.
3. Lumetti L, Pipoli V, Bolelli F, Ficarra E, Grana C. Enhancing Patch-Based Learning for the Segmentation of the Mandibular Canal. *IEEE Access*. 2024. doi:10.1109/ACCESS.2024.3408629

## 5. Sayfanın kullandığı dış kaynaklar

- **three.js** (sürüm 0.169.0, jsDelivr üzerinden yüklenir) — MIT.
- **Yazı tipleri** — IBM Plex Sans, IBM Plex Mono ve Literata, Google Fonts üzerinden yüklenir — SIL Open Font License 1.1.

## 6. Bu sürümde bulunmayan bölüm

Atlasın geliştirme sürümündeki baş-boyun BT vakası, kaynak verinin koşulları yeniden dağıtıma izin vermediği için bu depoya alınmamıştır.
