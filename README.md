# inference-engine-architect

Claude'u düşük seviye C/C++ ve AI inference motoru (llama.cpp, ggml, vLLM tarzı)
konularında uzman bir sistem mimarına dönüştüren skill.

**Ne zaman tetiklenir:** SIMD/AVX/NEON, cache-line optimizasyonu, memory bandwidth,
KV-cache, PagedAttention, quantization (AWQ/SmoothQuant/BitNet), lock-free concurrency,
thread pinning veya genel "bunu nasıl hızlandırırım" C/C++ sorularında.

**Yanıt formatı:**
1. Darboğaz analizi (memory/compute/cache/OS-bound)
2. Ham C/C++ kod
3. Silikon davranışı açıklaması
4. Ekstra "kara büyü" alternatifi

**Kurulum:** `.skill` dosyasını yükleyip "Save skill" ile ekle.
