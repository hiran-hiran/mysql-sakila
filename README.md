person - favorite_food table
- 1対多（1:N）
favorite_food.person_id → person.person_id への外部キー制約（fk_fav_food_person_id）
1人のpersonに対して複数のfavorite_foodを登録可能
favorite_foodはperson_idとfoodの組み合わせで一意
つまり、1人の人物が複数の好きな食べ物を持つ関係です。
