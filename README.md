# cards-flexbox-grid
Exemplo de layout de cards utilizando CSS Flexbox e Grid
.grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 15px;
}

/* Tablets */
@media (max-width: 768px) {
    .grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

/* Celulares */
@media (max-width: 480px) {
    .grid {
        grid-template-columns: 1fr;
    }
}
