# Usecase-5
# Riyadh Housing Data Analysis

## Introduction

شراء المنزل المناسب هو قرار مهم يتطلب دراسة وتحليل بيانات السوق العقاري. يهدف هذا المشروع إلى تحليل بيانات العقارات في الرياض لمساعدة المشترين والمستثمرين على اتخاذ قرارات مبنية على بيانات دقيقة.

### Objectives:

- تحليل سوق العقارات في الرياض باستخدام أدوات تحليل البيانات المتقدمة.
- استكشاف العوامل التي تؤثر على أسعار الشقق السكنية.
- تقديم رؤى واضحة حول توزيع الأسعار والمساحات والأحياء الأكثر طلبًا.
- عرض النتائج بطريقة تفاعلية باستخدام Streamlit.

---

## Dataset Overview

تم استخدام ثلاث مجموعات بيانات من Kaggle تتضمن معلومات مفصلة عن العقارات في الرياض:

- [Apartments in Riyadh](https://www.kaggle.com/datasets/abdulmalikm/apartments-in-riyadh)
- [Riyadh Aqar Dataset](https://www.kaggle.com/datasets/myfaisal/riyadh-aqaar-dataset)
- [Riyadh Housing Data](https://www.kaggle.com/datasets/salmanshir/riyadhhousingdata)

---

## Exploratory Data Analysis (EDA)

1. Data Cleaning: Handling missing values, correcting errors, and addressing outliers.
2. Data Profiling: Applying seven types of data profiling.
3. Univariate Analysis: Examining individual variable distributions.
4. Bivariate/Multivariate Analysis: Studying relationships between variables.
5. Data Visualization: Creating meaningful insights with at least ten different charts.
6. Consistent Chart Styling: Applying a uniform color palette, titles, labels, and legends.
7. Interactive Storytelling: Presenting findings through a Streamlit dashboard with our data story.

---

## Key Insights

### Q1: What are the factors that significantly affect the total price of lands, apartments, and villas?
- **Lands**: The total price is primarily influenced by the price per square meter, with a moderate correlation to total area.
- **Villas**: Features like swimming pools, driver’s rooms, and elevators have a significant impact on pricing.
- **Apartments**: The number of rooms and bathrooms are key factors affecting the price.

### Q2: What type of land is most common in Riyadh?
- Residential lands are the most dominant category in Riyadh, followed by mixed-use and commercial lands. This indicates a strong demand for residential properties over commercial investments.

### Q3: Is there a relationship between space and price, with distinction in the number of rooms?
- There is a positive correlation between space and total price, though the relationship is not strictly linear.
- The number of rooms also plays a role, with more rooms generally increasing the price.
- Some properties with similar space show significant price variations due to additional amenities and location factors.

### Q4: Which neighborhoods have the most apartments?
- Al-Narjis and Al-Malqa have the highest number of apartments, making them prime residential locations.
- Other areas like Al-Arid and Al-Yasmeen also show high concentrations of apartments.
- Neighborhoods such as Al-Murooj, Al-Aqiq, and Al-Nafil have the least number of apartments, indicating lower-density developments.

### Additional Insights

1. **Distribution of apartments by neighborhood**: Al-Narjis and Al-Malqa have the largest share of apartments, indicating high demand in these areas.
2. **Relationship between space and price with room count distinction**: More spacious properties tend to have higher prices, but the number of rooms also plays a significant role.
3. **Price distribution by number of rooms**: The price varies significantly based on the number of rooms, with noticeable outliers in certain categories.
4. **Regional distribution of properties**: The highest concentration of properties is in the western and eastern parts of Riyadh, while the central area has the least availability.
5. **Most common property orientations**: North-facing properties are the most common, followed by east and west orientations, reflecting market preferences.
6. **Key factors influencing total price**: Amenities such as pools, driver rooms, and elevators have a strong correlation with higher property values.

---

## Team Members

- Tahani AlOtaibi
- Manar AlShaikh
- Meshal AlSanari
- Naser AlManaa

---

## Conclusion

تحليل سوق العقارات في الرياض يوضح وجود تفاوت في الأسعار حسب الموقع والمساحة. يمكن للمشترين والمستثمرين استخدام هذه البيانات لاتخاذ قرارات مدروسة بناءً على أنماط السوق الحالية.

مخرجات المشروع متاحة عبر واجهة تفاعلية وسرد قصصي لسهولة البحث والاستكشاف.


---

## Streamlit App:
https://st-hello-world-v5be87oaguyugqwjenf3fk.streamlit.app/
