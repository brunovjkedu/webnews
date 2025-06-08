# WebNews
As principais notícias do Brasil e do mundo, atualizadas em tempo real. Informação rápida, clara e confiável.

# Referencias Bootstrap e icones

## Instalacao

### Bootstrap CSS
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
```

### Bootstrap Icons
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" rel="stylesheet">
```

### Bootstrap JS (para o tooltip funcionar)
```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<script>
  // Inicializar tooltips
  const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]')
  tooltipTriggerList.forEach(el => new bootstrap.Tooltip(el))
</script>
```

## Exemplo Ícone com Tooltip

### Tecnologia
```html
<span class="fs-1" data-bs-toggle="tooltip" title="Tecnologia" aria-label="Ícone de Tecnologia">
  <i class="bi bi-cpu" role="img" aria-hidden="true"></i>
</span>
```

### Esportes
```html
<span class="fs-1" data-bs-toggle="tooltip" title="Esportes" aria-label="Ícone de Esportes">
  <i class="bi bi-trophy" role="img" aria-hidden="true"></i>
</span>
```