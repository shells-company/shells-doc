# التوثيق

يحتفظ هذا الدليل بتوثيق PRIME-RL. وهو منظم في الأقسام التالية:

- [**Entrypoints**](entrypoints.md) - نظرة عامة على المكوّنات الرئيسية (orchestrator، trainer، inference) وكيفية تشغيل SFT وRL والتقييمات
- [**Configs**](configs.md) - نظام التكوين باستخدام ملفات TOML، ووسائط سطر الأوامر، ومتغيرات البيئة
- [**Environments**](environments.md) - تثبيت واستخدام بيئات verifiers من Environments Hub
- [**Async Training**](async.md) - فهم التدريب غير المتزامن خارج السياسة ودلالات الخطوات
- [**Logging**](logging.md) - التسجيل باستخدام loguru وtorchrun وWeights & Biases
- [**Runs**](runs.md) - التدريب متعدد التشغيلات مع كائن Runs لمحوّلات LoRA المتزامنة
- [**Checkpointing**](checkpointing.md) - حفظ التدريب واستئنافه من نقاط التفتيش
- [**Benchmarking**](benchmarking.md) - قياس الأداء وقياس الإنتاجية
- [**Deployment**](deployment.md) - نشر التدريب على GPU واحد، وعدة GPU، وعناقيد متعددة العقد
- [**Troubleshooting**](troubleshooting.md) - المشاكل الشائعة وحلولها
