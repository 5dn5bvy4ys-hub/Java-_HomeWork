# مثال على Generics و Lower Bound في Java

## فكرة البرنامج

البرنامج  مثال بسيط على استخدام Generics في لغة Java، وبالتحديد Lower Bound باستخدام `? super Integer`.

## شرح الكود

- درت دالة اسمها `addNumbers` تستقبل قائمة تقدر تخزن أعداد من نوع Integer أو نوع أكبر منه في التسلسل الوراثي.
- استخدمت `list.add()` لإضافة ثلاثة أعداد، وهي 10 و20 و30.
- في الدالة `main` أنشأت قائمة من نوع `Number` باستخدام `ArrayList`.
- بعدين استدعيت الدالة `addNumbers` وبعثتلها القائمة.
- في النهاية طبعت القائمة باستخدام `System.out.println()`.

## الناتج

```text
[10, 20, 30]
```

## المفاهيم المستخدمة

- Generics
- Lower Bound Wildcard (`? super Integer`)
- ArrayList
- List
- Methods
